This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

>api react que consulta eventos, uso Context


## Context API

Con __Context API__ se puede pasar el state o funciones desde el componente principal hasta los hijos, sin la
necesidad de pasarlo por cada componente. Se permite actualizar el state desde el hijo (o ejecutar una función que lo actualice).

y porque usar __props__ y no __context api__?
Es mucho más sencillo utilizar *props* ya que no necesita configuración y por lo tanto, en apis pequeñas es preferible utilizar *props*.
Aunque muchas api utilizan ambas propiedades.

* Provider. Donde se crean los datos, state y funciones.
* Consumer. Donde se consumen los datos o se utilizan las funciones.


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

