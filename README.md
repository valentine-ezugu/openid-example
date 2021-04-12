# openid-example

Before focusing on the actual development, we'll have to register an OAuth 2.o Client with our OpenID Provider.

In this case, we'll use Google as the OpenID Provider. We can follow these instructions to register our client application on their platform. Notice that the openid scope is present by default.

The Redirect URI we set up in this process is an endpoint in our service: http://localhost:8081/login/oauth2/code/google.

We should obtain a Client Id and a Client Secret from this process.


https://www.baeldung.com/spring-security-openid-connect


https://console.cloud.google.com/apis/credentials?project=openid-example-310520

https://developers.google.com/identity/protocols/oauth2/openid-connect#appsetup
