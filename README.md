This is a sample Node.js application (sending email if any data is in db) that can be used as a task for [Heroku Scheduler][1]. 

You can read details on [Rafal Spacjer's blog][2]

[1]: https://devcenter.heroku.com/articles/scheduler
[2]: http://www.spacjer.com/blog/2014/02/10/defining-node-dot-js-task-for-heroku-scheduler/

> This fork runs the script as an npm script. Although my initial motivation was a matter of personal preference, the practical value is that this method is platform independent. The "shebang" method will only work on platforms where a shebang is supported (i.e. probably not Windows)