# DEPRECATED: bootstrap-year-calendar-bs4

A fully customizable year calendar widget, now for Bootstrap 4 !
You can find all details on the [official website](http://www.bootstrap-year-calendar.com/).

![alt tag](http://www.bootstrap-year-calendar.com/img/calendar.png)

Please note that this package is now **deprecated** and will not be maintained.

You should use [js-year-calendar](https://github.com/year-calendar/js-year-calendar) instead, a rewrite of the calendar by its original author dropping the Bootstrap and jQuery dependencies while offering the same features and look and feel.

## Requirements

This plugin requires the following libraries :
- Bootstrap v4.0.0 or later
- jQuery v1.8.0 or later

## Installation

You can get the widget using the following methods:
- From the [GitHub repository](https://github.com/anlambert/bootstrap-year-calendar-bs4/releases).
- From the Node package manager, using the following command: `npm install bootstrap-year-calendar-bs4`
- From the Yarn package manager, using the following command: `yarn install bootstrap-year-calendar-bs4`

## Usage

You can create a calendar using the following javascript code :
```
$('.calendar').calendar()
```
or
```
$('.calendar').calendar(options)
```
or with the `data-provide` html attribute
```
<div data-provide="calendar"></div>
```
