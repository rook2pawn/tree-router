# Tree Router - Nested Tree Fast and Efficient HTTP Routing at constant O(1) lookup with Nested Trees


## With [Express](https://github.com/expressjs/expressjs.com "Express")

    var TreeRouter = require('tree-router');
    var express = require('express');

    var router = TreeRouter();    
    var app = express();
    app.use(router);

## With [Router-Middleware](https://github.com/rook2pawn/router-middleware "Router Middleware")

    var TreeRouter = require('tree-router');
    var rm = require('router-middleware');

    var router = TreeRouter();    
    var app = rm();
    app.use(router);


#### Example

    var TreeRouter = require('tree-router');
    var router = TreeRouter();
    
    // configure 

    router.get('/user/detail',fn);
    router.get('/user/:id', fn2);
    router.post('/user/avatar', fn3);
