# Butterfly Server .NET ![Butterfly Logo](https://raw.githubusercontent.com/firesharkstudios/butterfly-server-dotnet/master/img/logo-40x40.png) 

> The Everything is Real-Time C# Backend for Web and Desktop Apps

![Demo](https://raw.githubusercontent.com/firesharkstudios/butterfly-server-dotnet/master/img/simple-chat-demo.gif) 

![Star Us](https://raw.githubusercontent.com/firesharkstudios/butterfly-server-dotnet/master/img/yellow-star-16x16.png) Please star this project if you find it interesting

# Examples...

- [Real-time Streaming Charts](https://github.com/firesharkstudios/butterfly-server-dotnet/tree/master/Butterfly.Example.RealtimeStreamingChart) - Shows a client with a real-time streaming chart updated from a server (uses [Smoothie Charts](http://smoothiecharts.org/))
- [Todo List Manager](https://github.com/firesharkstudios/butterfly-server-dotnet/tree/master/Butterfly.Example.Todo) - Shows multiple clients synchronized to the same todo list (uses [Vue.js](https://vuejs.org/), [Vuetify](https://vuetifyjs.com), [Cordova](https://cordova.apache.org/), and [Electron](https://electronjs.org/))
- [Hello World](https://github.com/firesharkstudios/butterfly-server-dotnet/tree/master/Butterfly.Example.HelloWorld) - Shows a "Hello World" alert box in a client

# Key Components...

- [Database](https://butterflyserver.io/#/?id=accessing-a-database) allows performing standard database operations **and** subscribing to data change events
- [Subscription Api](https://butterflyserver.io/#/?id=creating-a-subscription-api) allows clients to subscribe to real-time updates from the server
- [Web Api](https://butterflyserver.io/#/?id=creating-a-web-api) allows defining RESTful APIs

# Key Implementations...

Each component above can have multiple implementations...

- [Database](https://butterflyserver.io/#/?id=accessing-a-database) currently has implementations for [MySQL](https://butterflyserver.io/#/?id=using-mysql), [SQLite](https://butterflyserver.io/#/?id=using-sqlite), and [MS SQL Server](https://butterflyserver.io/#/?id=using-ms-sql-server)
- [Subscription Api](https://butterflyserver.io/#/?id=creating-a-subscription-api) and [Web Api](https://butterflyserver.io/#/?id=creating-a-web-api) currently has an [EmbedIO](https://butterflyserver.io/#/?id=using-embedio) web server implementation

# FAQ

- Targets *.NET Standard 2.0*
- Does **not** depend on ASP.NET
- Does **not** use polling

See https://butterflyserver.io for more details.