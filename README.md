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
