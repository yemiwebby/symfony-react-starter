## Getting started With React in Symfony Using Webpack Encore

![react-symfony](https://user-images.githubusercontent.com/19610753/45068794-0ee70d00-b0c1-11e8-9e6f-286aa06fb51e.png)

This is a Symfony - React starter built with Symfony and React, then powered by Webpack Encore. See the screenshot of what we will build below:

![sym-starter-768x446](https://user-images.githubusercontent.com/19610753/45068857-6d13f000-b0c1-11e8-8aee-d931508d8b7f.png)

## Link to tutorial
[Here](https://www.cloudways.com/blog/symfony-react-using-webpack-encore/)



## Getting Started

### Clone the repository
```bash
$ git clone https://github.com/yemiwebby/symfony-react-starter.git
```

### Change directory
```bash
$ cd symfony-react-starter
```

### Use composer to manage and install dependencies
```bash
$ composer install
```

### Install the frontend dependencies
Run the command below from the project's root directory in another terminal:

```bash
$ yarn install
```

Do ensure that you have two separate terminals opened on your machine. One of them will be used to start the Symfony app while the other will keep the frontend running.

### Start the application
#### Backend
```bash
$ php bin/console server:run
```

#### Frontend
```bash
 $ yarn run encore dev --watch
```

## Prerequisites
A basic knowledge of React and Object oriented programming with PHP will help you get the best out of this article. Do ensure that you have [Node.js](https://nodejs.org/en/) and [Yarn package manager](https://yarnpkg.com/lang/en/docs/install/#mac-stable) installed on your system.

## Built With

* [Symfony](https://symfony.com/) - Is a set of reusable PHP components
* [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
* [Webpack Encore](https://github.com/symfony/webpack-encore) - Webpack Encore is a simpler way to integrate Webpack into your application.