# tableau-react-internal

Tableau react js engine based in Cooper but using 2.0.3 (hacks for react already added)

Here is below valid options 


| Name  | Type  | Description |
| ------------- | ------------- | -------------|
| disableUrlActionsPopups   | bol                        | Indicates whether to suppress the execution of URL actions. This option does not prevent the URL action event from being raised. You can use this option to change what happens when a URL action occurs. If set to trueand you create an event listener for the URL_ACTION event, you can use an event listener handler to customize the actions. For example, you can direct the URL to appear in an iframeon your web page. See URL Action Example.
 |
| hideTabs                  | bol                        | Indicates whether tabs are hidden or shown.
 |
| hideToolbar               | bol                        | Indicates whether the toolbar is hidden or shown.

 |
| instanceIdToClone         | string                     |  Specifies the ID of an existing instance to make a copy (clone) of. This is useful if the user wants to continue analysis of an existing visualization without losing the state of the original. If the ID does not refer to an existing visualization, the cloned version is derived from the original visualization.

|
| height                    | string                     | Can be any valid CSS size specifier. If not specified, defaults to the published height of the view.

 |
| width                     | string                     | Can be any valid CSS size specifier. If not specified, defaults to the published height of the view. |
| device                    | string                     | Specifies a device layout for a dashboard, if it exists. Values can be default, desktop, tablet, or phone. If not specified, defaults to loading a layout based on the smallest dimension of the hosting iframe element.

 |
| "filter name"             | string                     | Apply a filter that you specify to the view when it is first rendered. For example, if you have an Academic Year filter and only want to display data for 2022, you might enter "Academic Year": "2022". For more information, see Filtering.
 |
| "onFirstInteractive"      | callback(e: TableauEvent)  |  Callback function that is invoked when the Viz object first becomes interactive. This is only called once, but it’s guaranteed to be called. If the Viz object is already interactive, it will be called immediately, but on a separate "thread."

|
| onFirstVizSizeKnown       | callback(e: VizResizeEvent)  | Callback function that's invoked when the size of the Viz object is known. You can use this callback to perform tasks such as resizing the elements surrounding the Viz object once the object's size has been established.

 |
| toolbarPosition           | ApiToolbarPosition  | Specifies the position of the toolbar, if it is shown. The values can be ApiToolbarPosition.Top or ApiToolbarPosition.Bottom.

 |
