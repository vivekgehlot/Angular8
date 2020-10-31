# Angular8

Angular community has released its latest version which is known as Angular 8. If you are familiar with previous version of Angular, it will not be difficult for you. You can easily upgrade your Angular CLI to version 8.

Angular 8 is a client-side TypeScript based framework which is used to create dynamic web applications. It is very similar to its previous versions except having some extensive features.

Angular 8 facilitates you to use standard dynamic import syntax instead of a custom string for lazy-loaded modules.


## Differential loading
Differential loading is a new feature that lets you use version 8 of the Angular CLI to create two different production bundles of your app. Attributes on the <script> tag in your index.html file let the browser request the most appropriate bundle; modern browsers will request a bundle that uses ES2015 JavaScript syntax and will be significantly smaller than the legacy bundle that uses ES5 syntax to maintain support for older browsers. Differential loading is enabled by default for new apps created with version 8 of the CLI, but you can easily enable this feature on your existing apps by upgrading to Angular 8, adding a browserlist configuration file, and setting the “target” option in your tsconfig.json file to “es2015”. The result? Your users with modern browsers get a smaller bundle that loads faster (and puts a bigger smile on their face).
