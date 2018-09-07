[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/selvinfehric/multi-select-combo-box)

# Multi select combo box

Multi select combo box for Polymer 2 apps based on vaadin-combo-box component

## Installation

The element can be installed using bower
```
    bower install selvinfehric/multi-select-combo-box
```
If you want to save it in bower.json file, remember to add flag `--save`
```
    bower install selvinfehric/multi-select-combo-box --save
```

## Usage

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="multi-select-combo-box.html">
    <link rel="import" href="../vaadin-combo-box/theme/lumo/vaadin-combo-box-light.html">
    <link rel="import" href="../vaadin-text-field/theme/lumo/vaadin-text-field.html">
    <style>
        multi-select-combo-box {
          height: 200px;
	        overflow:hidden;
        }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<multi-select-combo-box items='["Item 1", "Item 2", "Item 3", "Item 4"]'></multi-select-combo-box>
<multi-select-combo-box items='[{ "id": 1, "name": "Name1" }, { "id": 2, "name": "Name2" }, { "id": 3, "name": "Name3" }, { "id": 4, "name": "Name4" }, { "id": 5, "name": "Name5" }]' value-field="id" display-field="name"></multi-select-combo-box>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request 

## Credits

Credits go to https://github.com/tomivirkki answer on this issue https://github.com/vaadin/vaadin-combo-box/issues/88

## License

This project is licensed under the terms of the MIT license.