# update_*_stat.rb
These scripts update the persian page of wikis stats in wikimedia.

## Requirements
* ruby >= 1.9.3
* rubygems
* mediawiki-gateway
* unicode
* language_name.rb

## How to install
    $ bundle install
## How to config
Rename config.example.yml to config.yml and set your username and password.
* note: USERNAME and PASSWORD must be your username and password of wikimedia project.

## How to run
    $ update_*_stat.rb

* note: The asterisk mark could be the following:
 - wikibooks
 - wikimedia
 - wikinews
 - wikipedia
 - wikiquote
 - wikisource
 - wiktionary


## LICENSE
Scripts that help to improve wikimedia projects such as wikipedia, wiktionary and etc.
    Copyright (C) 2014  Hamed Ramezanian

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
