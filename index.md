---
layout: default
---

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](./another_page.html).
[iOS](./ios/default.html).
[Rigging](./3d/default.md).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# UIKit Elements 

## UIVIew 

An object that manages the content for an area on the screen. 
This is the fundamental building blocks of your app’s user interface (UI), and the UIView define the all behaviors that are common to all views.

### Programmatically creating a UIView

Basically to create a view you have to pass it’s frame to draw it on screen or you can say you need the initial size of the view.

```swift
// set the frame for the view
let initialFrame = CGRect(x: 0, y: 0, width: 300, height: 300)
// create the view with frame defined 
let myView = UIView(frame: initialFrame)
// set a background color 
myView.backgroundColor = .red
// adding it to the superview
view.addSubview(myView)
```



```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
