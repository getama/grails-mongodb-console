      _____           _ _       __  __                         _____  ____
     / ____|         (_) |     |  \/  |                       |  __ \|  _ \
    | |  __ _ __ __ _ _| |___  | \  / | ___  _ __   __ _  ___ | |  | | |_) |
    | | |_ | '__/ _` | | / __| | |\/| |/ _ \| '_ \ / _` |/ _ \| |  | |  _ <
    | |__| | | | (_| | | \__ \ | |  | | (_) | | | | (_| | (_) | |__| | |_) |
     \_____|_|  \__,_|_|_|___/ |_|  |_|\___/|_| |_|\__, |\___/|_____/|____/
                                                    __/ |
                                                   |___/
      _____                      _
     / ____|                    | |
    | |     ___  _ __  ___  ___ | | ___
    | |    / _ \| '_ \/ __|/ _ \| |/ _ \
    | |___| (_) | | | \__ \ (_) | |  __/
     \_____\___/|_| |_|___/\___/|_|\___|

# Grails MongoDB Console
This project intend to provide a grails plugin similar to the grails-dbconsole plugin but for MongoDB, built on the Groovy mongodb driver.
It will uses some of the latest technologies in JS/HTML5 to provide a powerful and ergonomic Web GUI (well, that's the goal at least) that will allow you to :
* Browse through the documents of any collection
* Create, remove or update any document
* Browse through any GridFS buckets with a dedicated UI, allowing upload, download and deletion of files
* Querying the DB using the JSON / TenGen syntax, or using a simplified Lucene-query-like string for simple queries
* View all the administrative stuffs, isMaster, serverStatus, replicasets, ...
* _[this list will expand with time, I guess]_

Please note that the project is at its early stage and is not yet actually usable, not all of the listed features are available yet,
but feel free to evaluate the plugin and maybe write some feedback :)

## Technologies
For the UI we're currently using :
* Angular JS 1.1.0
* ACE web text editor
* Twitter Bootstrap-based templates

## Installation
The plugin isn't yet available on the official Grails plugin repository so you can't pull the dependencies directly, we will add a first version of the plugin when
 the basic features are covered.

The plugin does not require the official mongodb-gorm plugin to work, but it will use the configured mongo bean if the plugin is installed in your project.
In any case, it pull the mongodb and GMongo dependencies to

## License

    Copyright 2012 the original author or authors.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.