# Petal Extension
![](/Petal.png/)

This extension is designed to program and drive the sensor series Petal (Flower Petal) micro:bit expansion sensors. To purchase the Petal, visit the [Elecfreaks Official Store](https://shop.elecfreaks.com/products/elecfreaks-petal-bit-for-micro-bit).

## Key Features
- **Color Recognition System:** An intuitive system using color-coded terminals simplifies sensor and port connections.

## Getting Started

### Installing the Extension

1. Launch MakeCode editor and click the "Extensions" icon.
2. Search for "Petal" or paste the link "https://github.com/elecfreaks/pxt-petal" to download and install the extension.

### Basic Examples

**Block Editor Example**

1. Drag the "forever" block into the script area.
2. Inside it, insert a "if...else..." logic control block.
3. In the condition part, insert the "Petal - buttonRead" block.
4. If the button is pressed, make the micro:bit display the pattern "Yes", otherwise display the pattern "No".

**JavaScript Example**

```JavaScript
basic.forever(function () {
    if (petal.buttonRead(petal.DigitalPort.J1)) {
        basic.showIcon(IconNames.Yes)
    } else {
        basic.showIcon(IconNames.No)
    }
})
```
## Advanced Applications

Explore advanced features such as in-depth sensor data retrieval. For detailed examples and explanations, please visit our [online tutorials](https://wiki.elecfreaks.com/microbit/petal-series/).

## Supported Targets

- PXT/micro:bit

## License

This extension is licensed under the MIT License.
