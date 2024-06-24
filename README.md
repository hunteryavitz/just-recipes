# just-recipes
---
This is a simple React Native app for trackingg favorite recipes.

## Objective
---
This app aims to provide a straight-forward and simple way to create and save recipes on a mobile device.

## Details
---
This app should have the following layout and functionality:

### Layout
---
The layout of the app should resemble as described below.

- [ ] MAIN screen
   - [ ] `route` list in navigation drawer with following items
      - [ ] `categories`
      - [ ] `favorites`
      - [ ] `settings`
   - [ ] `card` list represents `category` items
      - [ ] `category` card contains following components
         - [ ] `image` component of `category` item
         - [ ] `text` component of `category` item
   - [ ] `fab` add component
- [ ] CREATE CATEGORY screen
   - [ ] `dialog` components for creating `category` item
      - [ ] `image` upload for new `category` item
      - [ ] `text` component for new `category` item
      - [ ] `text block` component for new `category item
      - [ ] `cancel` button component
      - [ ] `create` button component
- [ ] CATEGORY screen
   - [ ] `card` list represents `recipe` items
      - [ ] `recipe` card contains following
        - [ ] `image` component of `recipe` item
        - [ ] `text` title of `recipe` item
- [ ] CREATE RECIPE screen
   - [ ] `dialog` components for creating `recipe`
      - [ ] `image` upload for new `recipe` item
      - [ ] `text` component for new `recipe` item
      - [ ] `text block` component for new `recipe item
      - [ ] `tag` component for new `recipe`
      - [ ] `cancel` button component
      - [ ] `create` button component
- [ ] RECIPE screen
   - [ ] `card` detail components for preparing item
      - [ ] `image` component of item
      - [ ] `text` component of item
      - [ ] `favorite` star component of item
      - [ ] `tag` list component for item
      - [ ] `ingredient` list component for item
      - [ ] `preparation` list component for item
- [ ] SETTINGS screen
   - [ ] displays following `option` components
      - [ ] tbd

### Functionality
---
The functionality of the app should operate as described below.

- [ ] MAIN screen
   - [ ] `navigate` to any parent screen
   - [ ] `category` card component to push to `recipe` screen
   - [ ] `fab` component to create new `category`
- [ ] CREATE CATEGORY screen
   - [ ] `image` component to add `image` for new `category` item
   - [ ] `text` component to add `title` for new `category` item
   - [ ] `text-block` component to add `description` for new `category` item
   - [ ] `cancel` button component to pop back to `main` screen
   - [ ] `create` button component to `create` new `category` item
- [ ] CATEGORY screen
   - [ ] `back` button component to pop to `main` screen
   - [ ] `recipe` component to push to `detail` screen for item
   - [ ] `fab` component to create new `recipe` item
- [ ] CREATE RECIPE screen
   - [ ] `image` component to add `image` for new `recipe` item
   - [ ] `text` component to add `title` for new `recipe` item
   - [ ] `text-block` component to add `description` for new `recipe` item
   - [ ] `cancel` button component to pop back to `category` screen
   - [ ] `create` button component to `create` new `recipe` item
- [ ] RECIPE screen
   - [ ] `back` button component to pop to `category` screen
   - [ ] `star` button component to add `recipe` to favorites
   - [ ] `scale` batch component to multiply measurements

## Summary
---
The first version of this app should provide the user with the means to track and organize favorite recipes.
