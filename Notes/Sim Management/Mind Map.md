# Sim management
## State
- **dispatcher**					 
		   	 
	send dispatch function to all reducers optional
	
- common reducers

	reducer to change state. a function to mutate state
	
	```js
	const stateMutator = (state,field,value){
		if(state[field])
			state[field] = value
	}
	```
	
- async thunks

	handle requests inside reducers and change state accordingly.
	act as a view model for the views
	
## API Requests
- react query
- rtk query
- request functions
## MVVM
- ~~Model~~ 
- View
	- forms
	- model props
	- dispatcher
	- hooks
		- run on specific inputs
- ViewModel
	- view logic
	- api calls
## Styles
- Chakra ui
	- Theme customization
- CSS variables
	- use chakra css variables
- SCSS
	- css modules 
	- DRY code
## Auth
- next js middlewares
	- handle user session
- localstorage 
	- local forage
	- pouchdb
- cookies
	- httpOnly

