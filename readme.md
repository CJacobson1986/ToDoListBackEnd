## Authentication-System

A Laravel-Boilerplate for the Technopathic Full-Stack Web Development series was used in the creation of this site.

This ToDoListBackEnd is created as a Back-End framework for ToDoList Front-End.

## Getting Started
To reuse this code as a framework, fork this repo and clone it onto your local computer. Then run `composer install` to install all of the necessary libraries.
```
git clone https://github.com/CJacobson1986/ToDoListBackEnd.git
cd ToDoListBackEnd
composer install
```

From there you should go ahead and generate a Controller `php artisan make:controller ToDoListBackEnd`. Next, you should change the .env.example file name to .env.

To start the server, simply do `php artisan serve`.


## Commands
To generate Controllers:
`php artisan make:controller ControllerName`

To migrate:
`php artisan migrate`

## Screenshot
![alt text](http://h4z.it/Image/c00525_ackEndTables.PNG "Capture 1")
![alt text](http://h4z.it/Image/600cf1_BackEndTasks.PNG "Capture 2")

## Author
Christopher Jacobson

## Thanks
Special thanks to Technopathic for his Laravel-Boilerplate and the original build scripts.

## License
MIT
