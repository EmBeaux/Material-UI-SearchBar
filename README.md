**Search Bar**
This is just a little search bar I made.

It utilizes **material-ui** and it should be fully dynamic you just have to change

__57 let namesObjects = this.state.groups.map(group => group.name);
58 this.setNameData(namesObjects)__

and also change

__33 browserHistory.push(`/groups/${searchObj.id}`)__

Instead of mapping `this.state.groups` map what ever object you want, in this situation I just wanted to search by group name.

Also change the `browserHistory.push()` to wherever you want to redirect to.
