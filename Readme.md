<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/199047075/22.1.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T802166)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Grid for Blazor - How to display a custom confirmation dialog 

The example uses the [DxPopup](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxPopup) to create a custom confirmation dialog that asks user to approve record deleting.

![Display a custom confirmation dialog before deleting a grid record](application-page.png)

This example demonstrates how to do the following:

- Create a custom confirmation dialog with the **Confirm** and **Cancel** [buttons](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxButton).
- Add a custom **Delete** button to a [DxGrid](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid) column.
- Display the confirmation dialog on the **Delete** button [click](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxButton.Click).
- Delete the record in the bound data source when a user clicks the **Confirm** button.

## Files to Look At

- [Index.razor](./CS/DataGridShowDeleteConfirmation/Pages/Index.razor)

## Documentation

- [Grid: Data Binding](https://docs.devexpress.com/Blazor/403737/grid/bind-to-data)
- [Grid: Edit Data and Validate Input](https://docs.devexpress.com/Blazor/403454/grid/edit-data-and-validate-input)
- [Show and Close a Popup](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxPopup#show-and-close-a-popup)

## More Examples

- [Grid for Blazor - How to edit a row on a separate page](https://supportcenter.devexpress.com/ticket/details/t802173/grid-for-blazor-how-to-edit-a-row-on-a-separate-page)