# Rails-RecipeApp

## See this app in action
[Heroku Address](http://gelei.herokuapp.com/)

Time spent: **20** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can login as chef
- [x] User can view existing recipe
- [x] User can sort existing recipe by ingredient or style
- [x] Logined Chef can create new recipe
- [x] Logined Chef can edit his/her own recipe
- [x] Recipe is viewed by paging ranked by timestamp/like/dislike
- [x] User can see all the chefs and chefs' Recipes
- [x] Logined User can like/dislike a recipe
- [x] Recipe is viewed by paging
- [x] Admin user will have the ability to delete/update any recipes

The following **optional** features are implemented:

- [ ] Logined User can add review to a recipe


## Steps to implement Reviews
- 1. Migration to create reviews table, body, type = text_field, two foreign key, reference chef_id, reference recipe_id
- 2. build the Review Model
- 3.Build the association, has_many and belongs_to
- 4.Test out association in rails console
- recipe.reviews
- chef.reviews
- 5.Create routes
- 6.Authenicated chefs can create reviews, before_action , require_user
- 7.associate a chef_id and recipe_id
- 8.DRY

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='Recipe.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Follow the Udemy Professional Ruby on Rails Developer Course[Link](https://www.udemy.com/pro-rubyonrails/learn/#/)

## License

Copyright [2016] [Gelei]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.