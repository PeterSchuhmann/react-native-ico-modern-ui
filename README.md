# Modern Ui Icons for React Native

### react-native-ico-modern-ui

1260 Vector Icons for React Native

<img src="./static/3d.png" alt="3d" width="150" height="150"> <img src="./static/acorn.png" alt="acorn" width="150" height="150"> <img src="./static/add-multiple.png" alt="add-multiple" width="150" height="150">

## List of icons

- [List of Modern Ui Icons](http://ico.simpleness.org/pack/modern-ui)

## Usage

```
import Icon from 'react-native-ico-modern-ui';


// Inside some view component
render() {
    return (
        <>
          <Icon name="3d" />
          <Icon name="acorn" height="40" width="40" />
          <Icon name="add-multiple" style={{color: 'red'}} />
          <Icon name="add-multiple" colors={{ "#000000": "#FFFFFF" }} />
          <Icon name="acorn" badge="10" />
          <Icon name="acorn" badge={{value: 'A', fontSize: 25, radius: 22, position:'top_left', color:'orange', backgroundColor:'blue'}}/>
          <Icon name="3d" background="circle" />
          <Icon name="3d" background={{ type: "button", color: 'green' }} />
        </>
    );
}

```

## Installation

#### yarn

```bash
yarn add react-native-ico-modern-ui react-native-svg
```

#### npm

```bash
npm install --save react-native-ico-modern-ui react-native-svg
```

### Link react-native-svg

```bash
react-native link react-native-svg
```

### pod install ( for iOS )

```
cd ios && pod install && cd ..
```

## API

### <Icon name [color width height background badge ...rest] />

Returns a SvgXml icon by name and group.

 name | optional | default value | description | examples
------|----------|---------------|-------------|---------
name | no |  | name of icon | "3d"
color | yes | | line color, css style | "#00ff00", "#0f0", "green"
colors | yes | | replace colors | {"#FFFFFF": "#000000"} // white to black
width | yes | 20 | width of the icon | 40
height | yes | 20 | height of the icon | 40
background | yes | | background type | "circle"
background | yes | | background object | {type: "circle", color: 'yellow'}
badge | yes | | badge string | "10"
badge | yes | | badge object | {value: 'A', fontSize: 25, radius: 22, position:'top_left', color:'orange', backgroundColor:'blue'}
...rest | yes | | other props | style={{backgroundColor: "#00f"}}

## Icons Made by

[Dave Gandy](https://www.flaticon.com/authors/dave-gandy)

## Created by

Dimitry Ivanov <2@ivanoff.org.ua> # curl -A cv ivanoff.org.ua
