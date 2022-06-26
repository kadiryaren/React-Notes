# React Notes

> react bootstrap usage 
https://blog.logrocket.com/using-bootstrap-with-react-tutorial-with-examples/

## ReactRouter Usage
``` javascript
import  './App.css';

import {BrowserRouter as Router,Routes, Route} from  "react-router-dom";
import Home from  './Home';
function App() {
	return (
		<>
			<Router>
			<Routes>
			<Route  path="/"  element={<Home  />}  />
			</Routes>
			</Router>
		</>
	);

}
```

