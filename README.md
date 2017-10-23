#1 step
create-react-app

#2 step
add required modules with adding to package.json

npm i --save react-redux redux redux-logger redux-thunk

#3 step 
Organization files structure for project



mkdir src/app && mkdir src/app/containers && mkdir src/app/store && mkdir src/app/actions && mkdir src/app/components && mkdir src/app/reducers && mkdir src/app/constants

mv src/App.* src/app/containers/

# replace in index.js path to App.js : src/app/containers/App
