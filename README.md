# Lab: 28 - Django CRUD

## Overview

Add full CRUD functionality to your bag of tricks by building a Django project that allows Creating, Reading, Updating and Deleting.

&nbsp;

## Feature Tasks and Requirements

### Model

- Create `snacks_crud_project` Django project
- Create `snacks` app
- Create `Snack` model
  - title field
  - purchaser field
  - description field
  - Register model with admin
- Create `SnackListView` that extends appropriate generic view
  - associated url path is an empty string
- Create `SnackDetailView` that extends appropriate generic view
  - associated url path is `<int:pk>/`
- Create `SnackCreateView` that extends appropriate generic view
  - associated url path is `create/`
- Create `SnackUpdateView` that extends appropriate generic view
  - associated url path is `<int:pk>/update/`
- Create `SnackDeleteView` that extends appropriate generic view
  - associated url path is `<int:pk>/delete/`
- Add urls to support all views, with appropriate names
- Add templates to support all views
- Add navigation links in appropriate locations to access all pages
- Make all necessary changes to project level files for project to run
  - In other words, make it work

&nbsp;

**PR Link**: <https://github.com/YAHIAQOUS/django-crud/pull/1>
