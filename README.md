# project-chef
Cooks apps using ingredients and recipes you specifies


Project Chef(also known as app-chef) is the ultimate project scaffolder you need.

It wil bootstrap a Laravel application using Event Sourcing architecture.

The ingredients are features you want like Login with Google, or Send mails with Mailgun.

Ingredients can be prepared into recipes allowing to quickly bootsrap a project with full working features.

Examples of Recipies could be Authentication(using ingredients like OAuth or Token/Session-Cookie based auth).

Simply install the `app-chef` package from composer and run a command to get a freshly served dish ready for you.

```bash
php artisan cook:init

php artisan cook:add-ingredient SanctumAuth

php artisan cook:add-recipe SocialLogins  Google,Facebook,Github

php artisan cook:serve
```
## Customization
App cook publishes the codes it generates so you can modify it to your taste.

Writing a custom ingredient is as simple as defining an interface, implementing it and publish the right events.

php artisan cook:add-recipe SanctumAuth
TODO: Read more on Event Sourcing and ifnd the best package to use for this project
