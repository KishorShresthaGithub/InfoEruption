# Sim management
  
## State
- dispatcher  

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
	act as a view controller for the views.
	
	use the dispatch function to change other state
	
## API Requests
- react query
	- fetch data
	- provide data to component tree
		
- request functions
	- prepare payload
	- error handling
	
	create function to complete requests to API. 
	type the arguments according to the API specification
	type the return type
	handle the responses using a function and mostly in async thunks
	unit tests the api requests
	
- API flow
	
	Discuss the API flow and payload information first. and note it down
	Build functions and test the functions

## MVVM
- ~~Model~~ 

	this is not required at the moment. 
- View
	- forms
		- components
			
			  > Views contain a state or model state, but a component's state is it's props. 
		- validation
		- multi step
		
		final form to handle rendering 
		properly modularize validation and formatting
		
	- model props
		- hooks
			- run on specific inputs
			- perform state change on submit
		
	- actions
	
		actions must have an optional dispatch argument
		
- ViewModel
	- redux state
		
		the view model is the redux state
		
	- view logic

		written mostly in actions
		common action to update state fields
		
	- api calls
		
		use async thunks to perform api calls
		
## Styles
- Chakra UI
	- theme customization
	- better components
		- component logic from previous projects
- Layout
	- flex box layout
	- mobile layout
- SCSS
	 - CSS variables
		- use chakra css variables in 
		- map chakra variables to scss variables
	- DRY code
	
## Misc
- next js middlewares
	- handle user session
		- use local solution for now
		- user data provider
		
- Storage 
	- local forage
		- indexed db
			- workbox integration
	- rxstore
		- research rxStore	
	- pouchdb
		- next js server side solution
- cookies
	- httpOnly
	- access control



 


