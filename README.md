paper-collapse-radio-group [![Bower version](https://badge.fury.io/bo/paper-collapse-radio-group.svg)](http://badge.fury.io/bo/paper-collapse-radio-group) [![Travis state](https://travis-ci.org/Collaborne/paper-collapse-radio-group.svg?branch=master)](https://travis-ci.org/Collaborne/paper-collapse-radio-group) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/Collaborne/paper-collapse-radio-group)

[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/Collabornepaper-collapse-radio-group)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/Collabornepaper-collapse-radio-group.svg)](https://vaadin.com/directory/component/Collabornepaper-collapse-radio-group)
=========

A material design radio group that can be collapsed. This element is built for [Polymer](https://www.polymer-project.org).

To use the element:

`bower install paper-collapse-radio-group`

<!--
```
<custom-element-demo>
  <dom-bind id="app">
    <template>
        <link rel="import" href="paper-collapse-radio-group.html">
        <next-code-block></next-code-block>
    </template>
  </dom-bind>
</custom-element-demo>
```
-->
```html
<paper-collapse-radio-group items="[[items]]"></paper-collapse-radio-group>

<script>
    items = [
        { id: 'public', name: 'Public', description: 'Everybody has access' },
        { id: 'private', name: 'Private', description: 'Only internal people have access' }
    ];
</script>
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
