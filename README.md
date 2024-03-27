## CircularSpinner

A small SwiftUI package for drawing an animated circular spinner. Enjoy!

🚧 This package is under development.

CircularSpinner is a stroked circle with an animated puck in its foreground that infinitely spins. The foreground and background can be any ShapeStyle.  By default, the spinner will fill its container's size.

#### API
 
You can create a simple spinner using the default initalizer parameters:
```Swift
CircularSpinner()
```

You can also customize the animation timing and styling:
```Swift
CircularSpinner(
    animationDuration: 1.5,
    diameter: 60,
    backgroundStyle: Color.teal,
    foregroundStyle: LinearGradient(
        colors: [.purple, .red],
        startPoint: .leading,
        endPoint: .trailing
    )
)
``` 