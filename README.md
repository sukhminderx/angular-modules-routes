# angular-modules-routes
Modules
1.	Introduction
2.	Difference from JS modules
3.	Common modules from angular
a.	BrowserModule
b.	CommonModule
c.	FormsModule
d.	ReactiveFormsModule
e.	HttpClientModule
f.	RouterModule
g.	BrowserAnimationsModule
4.	Root module and Feature modules
5.	@NgModule decorator
6.	Decorator metadata
a.	declarations
b.	imports
c.	providers
d.	bootstrap
e.	exports
7.	entryComponents
8.	forRoot vs forChild
9.	Standalone components

Routing
1.	Introduction
2.	RouterModule
3.	Defining AppRoutingModule, routes array
4.	Setting up wildcard routes and redirectTo, src\app\app-routing.module.ts
5.	Routing directives – router-outlet, routerLink, routerLinkActive, src\app\app.component.html
6.	Getting route information, ActivatedRoute, paramMap, queryParams: src\app\heroes\hero-detail\hero-detail.component.ts . Show how to debug
7.	Router service. Back button in hero-detail.component.ts
8.	Nesting Routes. Introduction. src\app\admin\admin-routing.module.ts
9.	 Lazy-loading feature modules. Demonstration: loadChildren: () => import('./crisis-center/crisis-center.module')
10.	 Route guards. src\app\app-routing.module.ts admin module and auth
 Demonstration in inspect: without guard success, admin module doesnot load, login component will be shown.
Other guards added in src\app\admin\admin-routing.module.ts
a.	canActivate
b.	canDeactivate
c.	canLoad
d.	canActivateChild
11.	 Resolve. 
12.	 LocationStrategy
