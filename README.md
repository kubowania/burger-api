# burger-api
My Burger Api


Hello everyone! In this weeks video I show you how to make your own mock version of an API and deploy it onto the internet in just a few easy steps. This is a super stripped down version, so has no routing/controllers. This is thanks to the https://github.com/typicode/json-server​ package. Where you can get a mock REST API with zero coding in less than 30 seconds.

For those of you wishing to check it out live visit [here](https://my-burger-api.herokuapp.com/)

A lot of you are wondering if you can interact with this database. Yes you can. You can make GET, POST, PUT, DELETE etc requests to it. You can even get an individual burger. For example if I want to get the Tribute Burger, which has an ID of 0, I would write: 

```
fetch('https://my-burger-api.herokuapp.com/burgers/0')
  .then(response => response.json())
  .then(data => console.log(data));
```

For those of you who would like to add a burger to my database, please make a pull request here, following the same format as discussed on [this video.](https://youtu.be/FLnxgSZ0DG4)

If you did like the video tutorial, please hit the Like and Subscribe button so I know to make more!

* Twitter: https://twitter.com/ania_kubow
* YouTube: https://youtube.com/aniakubow
* Instagram: https://instagram.com/aniakubow

#burgerAPI
