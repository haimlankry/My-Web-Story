## My Web Story

# the evolution of the web through my eye as a web developer

I've started to look for my next framework, environment, language... for web application development.
After meny years of using Microsoft Visual Studio, coding c#, asp.net for IIS & MS-SQL on windows machines, I'm looking for an open-source solution.
I decided that my next fullstuck template will be node.js based.
front-end: Vue.js [Shell](https://developers.google.com/web/updates/2015/11/app-shell) that supports most [PWA](https://developers.google.com/web/progressive-web-apps/) features on client side.
server-side: Koa.js for REST API.

In order to understend the current web technology arichtecture let's take a brief of the [evolution of the web](http://www.evolutionoftheweb.com) or "[FROM STATIC TO DYNAMIC](http://royal.pingdom.com/2007/12/07/a-history-of-the-dynamic-web)".

My first server side language was ASP3.
Things got match better when .NET born, the simple WS SOAP based integration, OOP, separation between layout and logic was great!
But the basic architecture did not chage, Microsoft ASP.NET (web forms) was still postback based, witch mean low performence specially because the IIS renders the whole page for every click.
Since then, more and more open source libraries take significant part on both client and server side and Microsoft release MVC and other open source inspired or combind starter-kits and good solutions like web api.

The old school architecture was to render the HTML for every click, and then load the complete page.
The current architecture is a Single Page client Application project (Server Side Rendering) that makes Http json/bson request to REST APIs from different sources, some public and some Token based - the SPA layout loads only one time, and content change by replacing only the data inside the selected layout commponent, driven by a callback response or user action.




Reading [GitLab](https://about.gitlab.com/2016/10/20/why-we-chose-vue/), [harryho article](https://medium.com/@harryho2/angular-vs-react-vs-vue-f470f5b74bf6), https://www.academind.com/articles/javascript/angular-vs-reactjs-vs-vuejs/ and meny more 'VS' articles i've choose vue.js as my next front end technology.





