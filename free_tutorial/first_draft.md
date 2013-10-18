Rails environment setup (including RVM)
Sublime setup


```
rails new TheStartupCommunity
```

`cd TheStartupCommunity`

`rails s`

In your browser visit `localhost:3000`

`rails g controller home index`

Open the app files in sublime: `subl .`

Go to *config/routes.rb* and delete all but first and last lines. Add `root 'home#index'`.

Looks like:

````
TheStartupCommunity::Application.routes.draw do
  root 'home#index'
end
````