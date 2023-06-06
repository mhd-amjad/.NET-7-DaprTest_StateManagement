# .NET-7-DaprTest_StateManagement
Simple .NET 7 project  integrated to Dapr to test Dapr state management.

It is a simple counter uses dapr state management building block to save the counter state in a state store so each time you run the application you will notice that the counter is not reset to 0.

- To run this project you have to have the .NET 7  SDK as well Dapr CLI installed to your machine.
- Navigate to the project folder and run this command :  
  dapr run --app-id DaprTest dotnet run
