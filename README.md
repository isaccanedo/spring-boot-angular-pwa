# Spring Boot API with Angular PWA
 
Example app that shows how to create a Spring Boot API and display its data with an Angular PWA that works offline.

To see how this application was created, please read [Build Your First Progressive Web Application with Angular and Spring Boot](http://developer.okta.com/blog/2017/05/09/progressive-web-applications-with-angular-and-spring-boot) on the Okta Developer blog.

To run the server, cd into the `server` folder and run `mvn spring-boot:run`.

To run the client, cd into the `client` folder and run `npm install && ng serve`. Open <http://localhost:4200> to load initial data. Use Chrome Developer Tool to toggle offline in the Network tab and prove that it works offline.

# Então, o que é um PWA?
Os PWAs aproveitam o Transport Layer Security (TLS), manifestos de aplicativos da web e service workers para tornar um aplicativo instalável com recursos offline. Em outras palavras, um PWA é como um aplicativo nativo em seu telefone, mas é construído com tecnologias da web como HTML5, JavaScript e CSS3. Se construído corretamente, um PWA é indistinguível de um aplicativo nativo.

# Use Progressive Web Apps para criar aplicativos móveis melhores

Para combater os problemas que Alex Russell chama à tona e, finalmente, criar aplicativos móveis melhores, ele recomenda cinco técnicas:

- Implemente o padrão PRPL;
- Obtenha um Android desbloqueado de ~ $ 150-200 (por exemplo, Moto G4);
- Use chrome://inspect && chrome://inspect?tracing;
- Instale o Lighthouse e use-o para analisar seus aplicativos;
- Use a otimização da rede e da CPU do Chrome DevTools;

