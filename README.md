# RegionView
A simple Android Layout that enables drag and zoom for child Views. You can check out the explanation on [StackOverflow](https://stackoverflow.com/questions/9398057/android-move-a-view-on-touch-move-action-move/45241868#45241868).

### How to Use
The `RegionView` is a subclass of a `RelativeLayout`, which acts as its own `OnTouchListener`. Simply add a `View` to the `RegionView` and it will become immediately draggable and scalable. You may limit child `Views` to only be dragged and scaled within the confines of `RegionView` by calling `RegionView.setWrapContent(true)`.

### Supported API Levels
**Minimum API Level 11** (Honeycomb). *(Uses* `View.setScaleX()` *and* `View.setScaleY()`, *and the likes).*

## [@cawfree](https://twitter.com/cawfree)

Open source takes a lot of work! If this project has helped you, please consider [buying me a coffee](https://www.buymeacoffee.com/cawfree). ☕ 

<p align="center">
  <a href="https://www.buymeacoffee.com/cawfree">
    <img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy @cawfree a coffee" width="232" height="50" />
  </a>
</p>
