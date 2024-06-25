# .NET 8 Blazor Tutorial

### 12-callback-to-parent

Component needs to pass parameter back up to parent component.
This is done by implementing an EventCallback.

### 13-child-child-ref

Demonstrates where a child component can directly call another child components' method by using a reference.
This is done by:

1. Implement a `ClearFilter()` method in SearchBar component
2. On `Server.razor` add references to the SearchBar Component
3. Invoke `ClearFilter()` method inside a Handler in CityList component

## 14-cascading-param

If there are many levels of child component, it's tedious to pass down the parameter at each level.
Instead we use `CascadingValue` and `CascadingParameter` to cascade the parameter down to any child component.

## 15-template-component

We add re-usability to Edit Server component, by creating a template component `FieldComponent.razor`

## 16-typed-template

Here we add typed template component
Where we are able to have re-usable data element in the template as well
We need to provide the data type for template to work

We create `RepeaterComponent.razor` to replace the Server List

## 17-quick-grid

We create a Quick Grid Demo
To work with Quick Grid, we need to install the package.

Note:
`context` is a `Server`

Note:
QuickGrid Paginator doesn't work well
