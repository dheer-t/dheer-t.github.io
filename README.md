# Inventorious

Add Text here

## Skunk game
Users (who have access to the app), can specify items, members (who can borrow items), and create borrow orders for members. Orders can then be marked as returned or canceled, or renewed for 7 days from a user. Only authenticated users can access the app and make changes. User registration is disabled. Emails to a specified address are sent when an order is created, deleted, renewed, or marked as "returned".

## Installation Instructions

### Install Rails

* Make sure you have a Ruby version > 2.2.2 installed in your system
* Install [RubyGems](https://rubygems.org/pages/download)
* run ```gem install rails -v 5.0.2```

### Download Repo

* Download this repo, and unzip it
* ``` cd inventorious``` to cd into the folder
* ``` bundle ```
* ``` rails db:migrate db:seed ```



