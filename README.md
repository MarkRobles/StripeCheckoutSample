# Accept a Payment with Stripe Checkout

Stripe Checkout is the fastest way to get started with payments. Included are some basic build and run scripts you can use to start up the application.

I just modified a little the stripe sample codes to have a more complete flow to understand what happen.

## Running the sample

1. Build the server

~~~
dotnet restore
~~~

2. Run the server

~~~
dotnet run
~~~

3. Go to [http://localhost:4242/checkout.html](http://localhost:4242/checkout.html)


4. Before click on pay. Download the stripe CLI. Open the command line and be sure you are on the directory where stripe.exe is
4.1  now just type the commmands stripe login, stripe listen, stripe trigger : https://dashboard.stripe.com/test/webhooks/create?endpoint_location=local
