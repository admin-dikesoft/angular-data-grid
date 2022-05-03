
# DikeGrid

**An Angular Data Grid for Angular Developers**

The DikeGrid is a component engineered and built using the Angular Framework and some CDK behavior primitives. It is used to display and manipulate tabular data. You can provide your data from an array of JSON objects or a REST API. Nevertheless, you can define your custom DataSource.

The DikeGrid has ready-to-use features such as filtering, editing, selection, sorting, paging, column grouping, and row grouping, to mention a few. Apart from the key features, the DikeGrid is highly customizable. For instance, you can change the size of the column headers or the height of the content rows and customize many more properties.

The following image shows how our grid looks with some filters, row grouping, and edition enabled.

<img src="" title="DikeGrid Demo" style="max-width:100%;">

## License

The DikeGrid data grid is a commercial product and requires a paid license for use. Therefore, the DikeGrid product is subject to the terms and conditions defined in [DikeGrid's EULA](https://www.dikesoft.com/legal/dike-grid/license-agreement).

You can purchase a license at [www.dikesoft.com/dike-grid](https://www.dikesoft.com/dike-grid).

## Installation

```bash
npm install --save @dikesoft/angular-data-grid
```

## Key Features

* [Column definitions](https://docs.dikesoft.com/columns/column-definitions) &dash; To start using the DikeGrid, you may define the columns that comprise your tabular data. There are four types of columns depending on the data they hold. Apart from column definitions, you can group columns with no limit on nesting groups.
* [Customization](https://docs.dikesoft.com/fundamentals/grid-structure) &dash; You can customize the height of the column headers, the pagination row, and the group panel. In addition, you can make the DikeGrid shows a mat-elevation and the value of this elevation. You can also make vertical lines visible and customize many more properties.
* [Column Operations](https://docs.dikesoft.com/columns/column-sizing) &dash; Once you have defined which columns will comprise your DikeGrid instance, you can change their size or move them to any of the existing panels. Four panels are in each DikeGrid instance: left, center, right, or group panel. In addition, you can freeze any column in any panel.
* [Cell Formatting](https://docs.dikesoft.com/columns/column-definitions) &dash; By default, the DikeGrid shows every field value with predefined templates depending on the column types. Nevertheless, you can provide your custom templates for each defined column.
* [DataSource](https://docs.dikesoft.com/fundamentals/datasource) &dash; There are two types of data sources: In-Memory or Custom DataSource. The DikeGrid uses the In-Memory DataSource when you provide your data from a REST API or simply an array. However, you can define your custom DataSource if you need to take more control over your data. Therefore, a Custom DataSource must extend from the abstract class DataSource.
* [Filtering](https://docs.dikesoft.com/filtering/column-filters) &dash; The easiest way to allow the user to filter rows is by displaying a dedicated filter row that shows a textbox for each visible column. Or any column could show a context menu where the user can type their values for each filter condition. You can tell the DikeGrid which filter conditions to display and define each condition implementation.
* [Editing](https://docs.dikesoft.com/editing/row-edition) &dash; You can define which columns the user can edit. By default, the DikeGrid offers templates for fields edition, but you can provide your custom templates using the well-known ng-template. Furthermore, the user can toggle the edition mode at runtime.
* [Row Grouping](https://docs.dikesoft.com/rows/row-grouping) &dash; The DikeGrid allows the users to group rows by a field by dragging and dropping the specific column. Furthermore, row Grouping is not limited to a single column, and the DikeGrid will nest any number of groups and subgroups.
* [Sorting](https://docs.dikesoft.com/rows/row-sorting) &dash; The DikeGrid allows the user to order the rows by any column. Just tell DikeGrid which columns are sortable.
* [Paging](https://docs.dikesoft.com/rows/row-pagination) &dash; With paging implemented, the DikeGrid will only load the number of rows you specify in the DikeGrid\'s pageSize property. In addition, you can use paging when you provide your custom DataSource.
* [Selection](https://docs.dikesoft.com/rows/row-selection) &dash; The DikeGrid allows the user to select one or more rows through a column of checkboxes. You can specify which rows are selectable, defining the criteria the rows must meet.
* [Theming](https://docs.dikesoft.com/fundamentals/theming) &dash; The DikeGrid bases its theming process on the Angular Material\'s Theming System, allowing you to apply the same structure the Angular Material components use.

## Resources

[Getting Started with DikeGrid](https://docs.dikesoft.com/getting-started/quick-start-tutorial)

[DikeGrid product page](https://www.dikesoft.com/dike-grid)

[DikeGrid product docs](https://docs.dikesoft.com/)

## Demos

You can visit our [complete demo](https://www.dikesoft.com/dike-grid-demo), which contains 22 columns. Moreover, you can generate up to 100K rows.

Furthermore, we have created one [live example](https://demos.dikesoft.com/dike-grid/getting-started) for each section in the [documentation](https://docs.dikesoft.com/).

## Support

For any issues you might encounter while working with the DikeGrid, please email support@dikesoft.com

*Copyright © 2022 Dikesoft. All rights reserved.*
