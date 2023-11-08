import React from 'react';
import './App.css';
import teste from './actions/teste';

function App() {
 return (
    <div className="App">
      <header className="App-header">
        <p>{teste()}</p>
      </header>
    </div>
 );
}

export default App;
