paper-collapse-radio-group [![Bower version](https://badge.fury.io/bo/paper-collapse-radio-group.svg)](http://badge.fury.io/bo/paper-collapse-radio-group) [![Travis state](https://travis-ci.org/Collaborne/paper-collapse-radio-group.svg?branch=master)](https://travis-ci.org/Collaborne/paper-collapse-radio-group)
=========

A material design radio group that can be collapsed. This element is built for [Polymer 1.x](https://www.polymer-project.org).

![Screenshot](/doc/screenshot.png "Screenshot")


## Properties

Property         | Type    | Description                                    
---------------- | ------- | -----------------------------------------------
**items**        | Array   | Array of items that is shown. An item needs to have an ID and a name; and can have an optional description
**selected**     | String  | ID of the selected item
**selectedItem** | Object  | Item selected by the user
**opened**       | Boolean | True if the group is currently opened



## Usage

`bower install paper-collapse-radio-group`

```html
<paper-collapse-radio-group icon="hardware:security" items=[[items]]></paper-collapse-radio-group>
```


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
