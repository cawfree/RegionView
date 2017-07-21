# RegionView
A simple Android Layout that enables drag and zoom for child Views. You can check out the explanation on [StackOverflow](https://stackoverflow.com/questions/9398057/android-move-a-view-on-touch-move-action-move/45241868#45241868).

### How to Use
The `RegionView` is a subclass of a `RelativeLayout`, which acts as its own `OnTouchListener`. Simply add a `View` to the `RegionView` and it will become immediately draggable and scalable. You may limit child `Views` to only be dragged and scaled within the confines of `RegionView` by calling `RegionView.setsetWrapContent(true)`.

### Supported API Levels
**Minimum API Level 11** (Honeycomb). *(Uses* `View.setScaleX()` *and* `View.setScaleY()`, *and the likes).*
