<!--
    This source file is part of the open source project
    ExpressionEngine User Guide (https://github.com/ExpressionEngine/ExpressionEngine-User-Guide)

    @link      https://expressionengine.com/
    @copyright Copyright (c) 2003-2020, Packet Tide, LLC (https://packettide.com)
    @license   https://expressionengine.com/license Licensed under Apache License, Version 2.0
-->

# Database Tools

[TOC]

## Database Backup Utility

**Control Panel Location: `Tools > Utilities > Back Up Database`**

Tip: Two ways to back up your ExpressionEngine Database
<div class="video-wrapper">
<iframe src="https://www.youtube.com/embed/oKAEyqH1lts?si=P0O4_7QTfILYqylh" title="Two ways to back up your ExpressionEngine Database" width="1920" height="1080" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

This utility allows you to make simple SQL dump backups of your ExpressionEngine database. For file backups, or more robust and automated database backup options, please refer to [Back-up your ExpressionEngine database and files](general/database-backup.md).

When you click "Back Up Database", a SQL dump will be created and stored in your `system/user/cache/` folder, named based on the date and time of the backup, e.g.: `my_database_2017-10-20_09h20mPDT.sql`

## SQL Manager

**Control Panel Location: `Tools > Utilities > SQL Manager`**

This section of the Control Panel allows you to manage your database. The main SQL Manager screen shows a table of your basic database information and a list of tables.

By selecting the checkbox next to a table and picking an option from the dropdown at the bottom a table can be optimized or repaired, if necessary.

Click the "eye" icon to browse the table. From there, you can search the table for the content you are interested in viewing.

## SQL Query Form

**Control Panel Location: `Tools > Utilities > Query Form`**

This section presents a form that you can use to submit any standard database query. This feature is intended for **advanced** users since any changes you may make with a query are permanent.

Buttons at the bottom of the form can be used to provide you with a base query for many commonly used queries.

By default MySQL query errors are displayed.

![SQL Query Form](_images/utilities-query.png)
