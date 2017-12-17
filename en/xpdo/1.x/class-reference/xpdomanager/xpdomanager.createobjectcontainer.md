---
title: "xPDOManager.createObjectContainer"
_old_id: "1620"
_old_uri: "1.x/class-reference/xpdomanager/xpdomanager.createobjectcontainer"
---

xPDOManager::createObjectContainer()
------------------------------------

Creates the container for a persistent data object. In this implementation, a source container is a synonym for a MySQL database table. The table name will be generated by the schema.

Syntax
------

API Docs: [http://api.modxcms.com/xpdo/om-mysql/xPDOManager\_mysql.html#createObjectContainer](http://api.modxcms.com/xpdo/om-mysql/xPDOManager_mysql.html#createObjectContainer)

```
<pre class="brush: php">
void createObjectContainer (string $className)

```Examples
--------

Create the table for the class 'Person':

```
<pre class="brush: php">
$manager = $xpdo->getManager();
$manager->createObjectContainer('Person');

```