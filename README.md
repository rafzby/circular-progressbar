# Circular Progress Bar
Circular progressbar written in QML based on Canvas

![example](https://i.imgur.com/XfZihLw.png)

## Usage

```sh
CircularProgressBar {
            id: progress
            lineWidth: 10
            value: 0.5
            size: 150
            secondaryColor: "#e0e0e0"
            primaryColor: "#29b6f6"
}
```

### Property description

| Name | Type | Example | Description |
| ------ | ------ | ------ | ------ | 
| size | int | 150 | The size of the component (width and height) |
| lineWidth | int | 5 | The width of the progressbar line |
| value | real | 0.5 | The value of progress (from 0 to 1) |
| primaryColor | color | #29b6f6 | The color of the circle describing the progress |
| secondaryColor | color | #e0e0e0 | The color of the background circle |
| animationDuration | int | 300 |  The duration of the progress animation, in milliseconds |


License
----
[LGPL-3.0](https://github.com/rafzby/circular-progressbar/blob/master/LICENSE)

