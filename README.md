## One-way Data Binding
One-way data binding will bind the data from the component to the view (DOM) or from view to the component. One-way data binding is unidirectional. You can only bind the data from component to the view or from view to the component.

#### From Component to View
There are different techniques of data binding which use one-way data binding to bind data from component to view. Below are some of the techniques, which uses one-way data binding.

#### 1. Interpolation Binding: 
* Interpolation refers to binding expressions into marked up language.
```
<h3>{{title}}</h3>
```
#### 2. Property Binding: 
* Property binding is used to set a property of a view element. 
* The binding sets the property to the value of a template expression.

```
<img [src]="srcURL" />
```

#### 3. Attribute Binding: 
* Attribute binding is used to set a attribute property of a view element.
#### 4. Class Binding: 
* Class binding is used to set a class property of a view element.
#### 5. Style Binding: 
* Style binding is used to set a style of a view element.

## Two-way Data Binding
* Two-way data binding in Angular will help users to exchange data from the component to view and from view to the component. It will help users to establish communication bi-directionally.
```
<input type="text" [(ngModel)]="username" required/>
```
