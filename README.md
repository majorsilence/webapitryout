# webapitryout
Repo to test out webapi http://www.asp.net/web-api

Following tutorial found at http://www.asp.net/web-api/overview/getting-started-with-aspnet-web-api/tutorial-your-first-web-api

Browse http://localhost:51033/api/products

## Apply basic authentication filter

Use basic authentication filter found at http://weblog.west-wind.com/posts/2013/Apr/18/A-WebAPI-Basic-Authentication-Authorization-Filter

### Per Class
[MyBasicAuthenticationFilter]
public class YourController : ApiController

### Globally
GlobalConfiguration.Configuration.Filters.Add(new MyBasicAuthenticationFilter());



