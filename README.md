---
typora-copy-images-to: ./assets
typora-root-url: .
---

![badge](https://img.shields.io/badge/mendix-5.19.0-green.svg)
![badge](https://img.shields.io/badge/mendix-6.10.9-green.svg)
![badge](https://img.shields.io/badge/mobile-friendly-green.svg)

# Custom Input Mask

##### (formerly known as InputBoxOctober)



![E8F59EBB-2CC9-4728-8969-5E7DD1C66A28](/assets/E8F59EBB-2CC9-4728-8969-5E7DD1C66A28.png)


### Installation

1. Install the widget in your project
2. Include the **DecimalStyle** widget on a page where you'd like to display your styled decimal
3. Configure the widget properties:
    - `Decimal Field` : The attribute you want to display
    - `Before|After|Prepend Classname` : The classname to add to the `<span>` (characters) before the decimal, after the decimal, and to the prepended text, respectively
    - `Before Prepend` : The text to prepend to the value (use this for a `$`, etc)
    - `Decimal Places` : The number of decimal places to display

    ![B7FBB9EF-46BD-42CC-BE94-DCF686DBABBE](/assets/B7FBB9EF-46BD-42CC-BE94-DCF686DBABBE.png)

### Typical usage scenario

- to add styling to both sides of a decimal (so you can format dollars & cents differently, etc without adding more attributes to your domain model)

### Known Limitations

- none at this time.

###### Based on the Mendix Widget Boilerplate

See [AppStoreWidgetBoilerplate](https://github.com/mendix/AppStoreWidgetBoilerplate/) for an example
