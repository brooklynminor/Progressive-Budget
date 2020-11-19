# Progressive-Budget

The budgeting app keeps track of personal finances. By utilize IndexedDB, cache API, and Service Workers, provides an offline experience for the application.

## Overview
Occasionally, a user will access the web from older devices with a slower connection. Web applications are growing continuessly in size and complexity, therefore, as do the load times. In order to ensure the experience is user-friendly, it is important ot optimize the performance.
Chrome Devtools is the primary tool for measuring the performance. Devtools monitors network trafficing and inspect the resource size downloaded (ie. HTML, CSS, JavaScript and images).

Progressive Web Apps (PWAs) aim to blend the benefits of a traditional browser experience with those of a mobile application. PWAs utilize the Service Worker and Cache APIs to cache assets and API responses to ensure applications work without an internet connection.

## Key Concepts

* Chrome Tools

* Lazy Loading

* Minification

* Compression

* PWAs

* Service Workers

* Webpack

## Algorithms

Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.
```
mongoose.connect(
  process.env.MONGODB_URI || 'mongodb://localhost/budget_db',
 {
  useNewUrlParser: true,
  useUnifiedTopology: true,
  useCreateIndex: true,
  useFindAndModify: false
});
```
 The findAndModify command modifies and returns a single document. By default, the returned document does not include modifications made on the update. To return the document with the modifications made on the update, new options is used.

The user will be able to add expenses and deposits to a budget with or without a connection. When entering transactions offline, the application will populate the total when brought back online. When offline, and the user enters a deposit, and the tracker is brought back online the entries are added. This is completed by right clicking inspect and selecting the toggle icon, from there the user is able to access the app offline or online. _An image is added to the assets folder as a demonstration._

## Installation

npm install and npm init are required to be installed through the terminal if there is no package.json, package-lock.json or node_modules presented. Upon created the repo the License MIT has been selected. Deployed  application with Heroku and MongoDB Atlas.

## License

  [License](https://choosealicense.com/licenses/mit)