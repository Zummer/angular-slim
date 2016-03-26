AngularJS + Slim2 RESTful application + RedbeanPHP ORM
A small CRUD application using Slim PHP framework
======================

<h1>Description</h1>
<p>
Проект подразределен на 2 отдельных проекта. Каждый из них работают на разных серверах и взаимодействуют через
кроссдоменные запросы, с использованием CORS.
</p>

<h1>Install</h1>

<div class="highlight">
<pre>
$ git clone https://github.com/Zummer/angular-slim.git
$ cd angular-slim
$ git submodule init
$ git submodule update
</pre>
</div>

<div class="highlight">
<pre>
$ cd test1
$ bower install
</pre>
</div>

<div class="highlight">
<pre>
$ cd rest1
$ composer install
</pre>
</div>

<p>
Demo frontend: http://test1.plottex.ru
Demo resources: http://rest1.plottex.ru/items
</p>