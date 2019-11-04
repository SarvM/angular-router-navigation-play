## Angular Routing

` What is navigation? `


* The browser is a familiar model of application navigation:

1. Enter a URL in the address bar and the browser navigates to a corresponding page.
2. Click links on the page and the browser navigates to a new page.
3. Click the browser's back and forward buttons and the browser navigates backward and forward through the history of pages you've seen.

`base href why?`

` A routed Angular application has one singleton instance of the Router service. `

* The order of the routes in the configuration matters and this is by design

* first-match wins strategy when matching routes

`Router Outlet`

* routerLink and routerLinkActive
* dynamic binding of path is possible through template expression

