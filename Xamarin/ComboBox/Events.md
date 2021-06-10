---
layout: post
title: Events in Syncfusion SfComboBox control in Xamarin.Forms
description: This section describes how to use different types of events and interactvity in SfComboBox control (Xamarin.Forms)
platform: Xamarin
control: SfComboBox
documentation: ug
---

# Events and Interactivity in Xamarin SfComboBox

## ValueChanged Event

You can perform operation, while changing the value of SfComboBox Text using the ValueChanged event. [`ValueChanged`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.ValueChangedEventHandler.html) event returns the changed value in SfComboBox.

The ValueChanged event returns the following argument.

<table>
<tr>
<th>Members</th>
<th>Description</th>
</tr>
<tr>
<td>Value</td>
<td>Displays changed value in SfComboBox</td>
</tr>
</table>

## SelectionChanged Event

The [`SelectionChanged`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.SelectionChangedEventHandler.html) event is used to notify when an item is selected from the suggestion list or when dynamically setting the SelectedIndex property of SfComboBox, the event is triggered. For more information, refer to [`this`](https://help.syncfusion.com/xamarin/combobox/retrieving-selected-values) link. The SelectionChanged event returns the following argument.

<table>
<tr>
<th>Members</th>
<th>Description</th>
</tr>
<tr>
<td>Value</td>
<td>Holds the selected items in SfComboBox</td>
</tr>
</table>

## SelectionChanging Event

The [`SelectionChanging`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.SelectionChangingEventHandler.html) event is used to notify, before the selection is going to changed by tapping the suggestion box or dynamically setting the SelectedIndex property of SfComboBox.The SelectionChanged event returns the following argument.

<table>
<tr>
<th>Members</th>
<th>Description</th>
</tr>
<tr>
<td>Value</td>
<td>Holds the selecting items in SfComboBox.</td>
</tr>
<tr>
<td>Cancel</td>
<td>Restricts the item to be selected.</td>
</tr>
</table>

## FocusChanged Event

The [`FocusChanged`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.FocusEventHandler.html) event occurs when the control gets the focus and loses the focus. The argument contains the following information.

<table>
<tr>
<th>Members</th>
<th>Description</th>
</tr>
<tr>
<td>HasFocus</td>
<td>Indicates whether the control is in focused state or not.</td>
</tr>
</table>

## FilterCollectionChanged Event

The [`FilterCollectionChanged`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.FilterCollectionChangedEventHandler.html) event is triggered whenever the items gets filtered in the suggestion.

For more information regarding this refer to [`this`](https://help.syncfusion.com/xamarin/combobox/dealing-with-suggestion-box) link. The FilterCollectionChanged event returns the following argument.

<table>
<tr>
<th>Members</th>
<th>Description</th>
</tr>
<tr>
<td>Value</td>
<td>Holds the filtered items in the suggestion.</td>
</tr>
</table>

## DropDownOpen Event

The [`DropDownOpen`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.DropDownOpenEventHandler.html) event occurs when the SfComboBox drop-down is opened.

## DropDownClosed Event

The [`DropDownClosed`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.DropDownClosedEventHandler.html) event occurs when the SfComboBox drop-down is closed.

## Completed Event

The [`Completed`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.CompletedEventHandler.html) event is raised when the user finalizes the text in the SfComboBox editable mode by pressing return key on the keyboard.

## Tapped Event

The [`Tapped`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.html#Syncfusion_XForms_ComboBox_SfComboBox_Tapped) event occurs when the SfComboBox is tapped in Non-editable mode.

## LoadMoreButtonTapped Event

The [`LoadMoreButtonTapped`](https://help.syncfusion.com/cr/xamarin/Syncfusion.XForms.ComboBox.SfComboBox.html#Syncfusion_XForms_ComboBox_SfComboBox_LoadMoreButtonTapped) can be triggered only when you tap on the load more button. For more information, refer to [`this`](https://help.syncfusion.com/xamarin/combobox/maximum-display-item-with-expander#load-more-button-tapped-event) link.