---
tags: runtime-mobileandreactiveweb;
summary: List Item Content is used to layout content such as icons, text, and actions inside a list in a readable way.
---

# List Item Content

You can use the List Item Content UI Pattern to quickly organize critical content in a readable way, helping the user understand the content. The List Item Content pattern is often used to organize content such as icons, text, and actions inside a list in a readable way.

![](<images/listitemcontent-1-ss.png>)

**How to use the List Item Content UI Pattern**

1. In Service Studio, in the Toolbox, search for `List Item Content`.

    The List Item Content widget is displayed.

    ![](<images/listitemcontent-2-ss.png>)

    If the UI widget does not display, it may be because you used a ready-made app, which deletes unused widgets from the module. To make additional widgets available in your app:

    a. Go to **Module > Manage dependencies**.

    b. Search for and select the relevant Producer, for example OutSystemsUI. Ensure Show All is selected. 

    c. On the Public elements for the selected Producer displayed on the right, ensure Show All is selected.
    
    d. Search for and select the element you want to add, and click **Apply**. 
    
    e. In Service Studio, in the Toolbox, search for the widget again.

1. From the Toolbox, drag the List Item Content widget into the Main Content area of your application's screen.

    ![](<images/listitemcontent-3-ss.png>)

1. Add the relevant content to the placeholders.

    In this example, we add some texts and icons. 

    ![](<images/listitemcontent-4-ss.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| Property |  Description |
|---|---|
| ExtendedClass (Text): Optional |  Adds custom style classes to the Pattern. You define your [custom style classes](../../../../../develop/ui/look-feel/css.md) in your application using CSS. <p>Examples <ul><li>_Blank_ - No custom styles are added (default value).</li><li>_"myclass"_ - Adds the _myclass_ style to the UI styles being applied.</li><li>_"myclass1 myclass2"_ - Adds the _myclass1_ and _myclass2_ styles to the UI styles being applied.</li></ul></p>You can also use the classes available on the OutSystems UI. For more information, see the [OutSystems UI Live Style Guide](https://outsystemsui.outsystems.com/StyleGuidePreview/Styles). |
