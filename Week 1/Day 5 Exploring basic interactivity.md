## Explore basic interactivity

On your project at **Components** > **Pages** folder open **Counter.razor** file. Here is the code for that file:


```html
@page "/counter"
@rendermode InteractiveServer

<PageTitle>Counter</PageTitle>

<h1>Counter</h1>

<p role="status">Current count: @currentCount</p>

<button class="btn btn-primary" @onclick="IncrementCount">Click me</button>

@code {
    private int currentCount = 0;

    private void IncrementCount()
    {
        currentCount++;
    }
}

```

## Explaining the code
- **@currentCount**: Displays the current value of the counter.
- **@onclick="IncrementCount"**: Binds the button click to the **IncrementCount** method.
- **IncrementCount()**: Increases the counter value by 1 each time the button is clicked.
- Blazor uses event binding **@onclick** to respond to user actions.
- The component maintains state **currentCount** and re-renders automatically when the state changes.
