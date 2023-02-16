## Welcome to "Hello World" with GitHub Actions

This course will walk you through writing your first action and using it with a workflow file. 

**Ready to get started? Navigate to the first issue.**


  <!--Tabs-->
<input id="tab1" type="radio" name="tabs" checked>
<label for="tab1">Tab 1</label>

<input id="tab2" type="radio" name="tabs">
<label for="tab2">Tab 2</label>

<input id="tab3" type="radio" name="tabs">
<label for="tab3">Tab 3</label>

<div id="tab-content1">
  <p>Tab 1 content goes here.</p>
</div>

<div id="tab-content2">
  <p>Tab 2 content goes here.</p>
</div>

<div id="tab-content3">
  <p>Tab 3 content goes here.</p>
</div>
<!--Tabs End-->

<style>
  /* Hide the tab content by default */
  [id^="tab-content"] {
    display: none;
  }

  /* Show the active tab content */
  #tab1:checked ~ #tab-content1,
  #tab2:checked ~ #tab-content2,
  #tab3:checked ~ #tab-content3 {
    display: block;
  }
</style>
