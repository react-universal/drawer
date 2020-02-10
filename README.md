<p align="center" style="margin-bottom: 0px !important;">
  <img width="600" src="https://raw.githubusercontent.com/react-universal/ripple/master/media/logo.jpg" alt="Material Bread logo" align="center">
</p>


A React Material Ripple component that works on the Web, Android, iOS, Electron, and anywhere else React Native is supported. This component is a part of the React Universal ecosystem of universal React and React Native components. Checkout the [React Universal docs](https://github.com/react-universal/react-universal) to learn more.


### [Storybook Demos](https://react-universal.github.io/ripple/?path=/story/*)



### Installation

```bash
npm i @reactuniversal/ripple --save
```

### Example

```
import React from 'react';
import { View, Text } from 'react-native';
import Ripple from '@reactuniversal/ripple';

export default function Page() {
    return (
      <View style={{flexDirection: 'row', flexWrap: 'wrap'}}>
        <Ripple
          rippleColor={'blue'}
          style={{
            width: 180,
            height: 250,
          }}>
          <Text>Click Me</Text>
        </Ripple>
      </View>
    );
}`;

```

#### Props

| Name                  | Description                                                      | Type   | Default |
| --------------------- | ---------------------------------------------------------------- | ------ | ------- |
| displayUntilPressOut     | Keep ripple at full size while holding press                           | bool | true    |
| disabled                 | Disables ripple                                                    | bool |         |
| onPress           | Callback on ripple                        | func   |         |
| rippleCentered                | Whether the ripple starts at the center of the component or where you clicked                                | bool   |     false    |
| rippleColor                | Color of ripple                                    | string | rgba(0, 0, 0, .87)      |
| rippleContainerBorderRadius | Border Radius of ripple           | number | 0       |
| rippleDuration                 | Animation Duration of ripple to fill the entire component                                            | duration |    400     |
| rippleOpacity            | Opacity of ripple                           | number |   0.3      |
| rippleSize                 | Determines the size of ripple | number |    0     |
| rippleSequential               | Ripple should start in sequence                                    | bool   |     false    |
| style     | Styles root element                         | object |     |
