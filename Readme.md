# Deploying React Apps
This guide will cover the steps to deploy a React app on Firebase Hosting. The topics covered include:

### Test Code
Before deploying a React app, it's essential to test the code to ensure that everything is working as expected. Running tests can help catch bugs and ensure that the app is functioning correctly.

### Optimize Code
Optimizing the code can help improve the performance of the app. One way to optimize the code is through lazy loading. Lazy loading allows the app to only load the necessary components, improving the app's load time.
**lazy loading**

#### Example
loader : ```loader: () => import('./pages/Blog').then(module => module.loader())```

Components imports : ``` const BlogPage = lazy(() => import('./pages/Blog')); ```

### Build App for Production
To deploy a React app, it's necessary to build the app for production. Building the app will create an optimized version of the app that can be deployed to a server.

```npm run build```

### Upload Production Code to Server
After building the app for production, it's time to upload the code to the server. In this guide, we'll be using Firebase Hosting to host the React app.

``` create project > build (HOSTING) > get started > follow CLI instructions```

### Configure Server
To deploy a React app on Firebase Hosting, it's necessary to configure the server. This involves setting up the Firebase project, installing the Firebase CLI, and configuring the app for deployment.

