# tonyspiro.com-react
The steps I took to create this version of my blog were:

1. Create a new bucket in [Cosmic JS](https://cosmicjs.com)
2. Export the data out of my WP blog using the [Cosmic JS WP Export plugin](https://github.com/cosmicjs/cosmicjs-wp-export)
3. Import the JSON file from the export into my Cosmic JS bucket
4. Build the React App

### Install
```
git clone https://github.com/tonyspiro/tonyspiro.com-react
cd tonyspiro.com-react
npm install
```
### Run webpack dev
```
npm run dev
```
Go to [http://localhost:8000/webpack-dev-server](http://localhost:8080/webpack-dev-server)
### Run production
```
npm start
```
Go to [http://localhost:8000](http://localhost:8000)