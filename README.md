# Ionic Select Searchbar

App created using the [Ionic 5 framework](https://ionicframework.com/docs) and the [Ionic Selectable search component](https://www.npmjs.com/package/ionic-selectable) to create a list of selectable elements.

## Table of contents

* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

* array of data are used to test selectable searches.

## Screenshots

![image](./img/selectable_search.png)

## Technologies

* [Ionic/angular v4.1.0](https://www.npmjs.com/package/@ionic/angular)

* [Ionic v5.7.0](https://ionicframework.com/)

* [Angular v7.2.0](https://angular.io/)

* [Ionic Selectables v4.4.1](https://www.npmjs.com/package/ionic-selectable)

## Setup

* To start the server on _localhost://8100_ type: 'ionic serve'

## Code Examples

```typescript
<ion-item>
  <ion-label>Group example</ion-label>

  <ionic-selectable
    [(ngModel)]="group"
      itemValueField="id"
      itemTextField="name"
      groupTextField="type"
      [items]="groups">

      <ng-template ionicSelectableGroupTemplate let-group="group">
        {{ group.text }}
      </ng-template>

  </ionic-selectable>
</ion-item>

```

## Features - ionic selectable

Features copied from Ionic component [documentation](https://www.npmjs.com/package/ionic-selectable):

* Single selection
* Multiple selection
* Search items
* Search items asynchronously
* Search by several item fields
* Forms
* InfiniteScroll
* VirtualScroll
* Templates
* Grouping items
* Editing, adding and deleting items
* Disabling items

## Status & To-do list

* Status: Working.

* To-do: try more of the functionality from the Ionic searchable select component.

## Inspiration

Project inspired by [Simon Grimm´s Youtube video: Ionic Searchable Select Component Customisation](https://www.youtube.com/watch?v=SO_AWrrmZlY)

## Contact

Repo created by [ABateman](https://www.andrewbateman.org) - feel free to contact me!
