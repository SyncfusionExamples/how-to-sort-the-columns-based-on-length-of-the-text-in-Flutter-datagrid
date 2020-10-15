## Custom sorting

The datagrid allows to sort columns based on custom logic. For each column, you can provide different sorting criteria by overriding the following methods from [DataGridSource](https://pub.dev/documentation/syncfusion_flutter_datagrid/latest/datagrid/DataGridSource-class.html),

* **[handleSort](https://pub.dev/documentation/syncfusion_flutter_datagrid/latest/datagrid/DataGridSource/handleSort.html)** : This method will be called when you tap the column header and sorting is being applied. You can override this method to provide the entire logic for sorting for columns.
* **[compare](https://pub.dev/documentation/syncfusion_flutter_datagrid/latest/datagrid/DataGridSource/compare.html)** : You can override this method to compare two objects and return the sorting order based on the criteria.

### Sort columns based on string length

This application shows how to perform custom sorting for the columns based on the string length by overriding the `handleSort` and `compare` method.