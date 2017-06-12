# Alarm Clock App

## Introduction

This application has a digital clock and ability to set alarm, as well as an indication that alarm has gon off

## Build/Usage Instructions

If you already have SASS and the node http-server module installed globally on your computer you can run this project with

```
npm run start
```

If you do not have SASS on your computer, you can install SASS (You should be able to search and get it installed, otherwise you can find out from the `package.json`)

If the SASS code is compiled and located at styles/styles.css you can launch this application with any basic server from the root directory of this project. 

Then visit [http://localhost:3000](http://localhost:3000)


## Improvement that can happen in the further

- Do not set duplicated alarm

- Some UI indicates that the alarm has gone off

- Responsive Design: I decided to go with a mobile first approach, but I'd like to alter the CSS to adapt to larger screen sizes

- Alarm Sorting: implement a sorting function so that alarms are order by when they will go off, there is no sorting implemented

- Manually dismissible alert feature

- Data Persistance: Alarm data can be stored in localStorage

- Support the feature to delete or edit a seted alarm