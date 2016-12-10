# Angular2Bootcamp

0. Create a model `Employee` with the following variables:
	- Id: number
	- Name: string
	- Position: string
	- Age: number
1. Create two components: `Employees` and `Employee` 
2. Create a service that returns a list of employees
3. Call the service from the `Employees` component to render all the employees' name. Don't forget to use Bootstrap styles.
4. Import Route module in the App.module
5. Add a routes for the `Employees` component and the default url (''). Also for the wildcard `**`
6. Add the `<router-outlet>` element in the main module
7. Change the template of Employees to wrap every employee in an anchor tag
8. Add the `routerLink` attribute to the anchors sending the Id
9. Add the route for the `Employee` component with the `id` parameter
10. In `Employee` import all the necessary modules, inject all the dependencies and run a forEach to obtain the `id` sent through parameter
11. Call the same service as above sending the `id` parameter to query all the related information and render it in the component
12. Add a back button