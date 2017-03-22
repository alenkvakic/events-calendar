[![Build Status](https://travis-ci.org/mpachnis/mp-calendar.svg?branch=master)](https://travis-ci.org/mpachnis/mp-calendar) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/mpachnis/mp-calendar)


### &lt;mp-calendar&gt;


## Demo

[mp-calendar docs & demo](http://minas.pachnis.com/projects/mp-calendar/bower_components/mp-calendar/)


### Install

```bash
# via bower
$ bower install mp-calendar
```

### Usage

Load the calendar

```html
<link rel="import" href="path_to_bower_components/mp-calendar/mp-calendar.html" />
```

<!--
```
<custom-element-demo>
    <template>
        <link rel="import" href="mp-calendar.html">
        <next-code-block></next-code-block>
    </template>
</custom-element-demo>
```
-->

add the calendar element

```html
<mp-calendar day-labels='["Su","Mo","Tu","We","Th","Fr","Sa"]'
             disable-prev-days
             show-days-in-month=42>
</mp-calendar>

```

### License

MIT License