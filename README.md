## tarc

```javascript
  import Taro from '@tarojs/taro';
  import { View, Text } from '@tarojs/components';
  
  export default class Test extends Taro.Component {
    render() {
      return (
        <View>
          <Text> Test </Text>
        </View>
      );
    }
  }
```

## tarcs
```javascript
import Taro from '@tarojs/taro';
import { View, Text } from '@tarojs/components';
import styles from './index.scss'

export default class Test extends Taro.Component {
  render() {
    return (
      <View className={styles.main}>
        <Text> Test </Text>
      </View>
    );
  }
}
```

## tarTCS
```javascript
import Taro from '@tarojs/taro';
import { View, Text } from '@tarojs/components';
import styles from './index.scss'

export default class Test extends Taro.Component {

config = {
navigationBarTitleText: '首页'
};

  render() {
    return (
      <View className={styles.main}>
        <Text> Test </Text>
      </View>
    );
  }
}

```

希望大家能将自己常用的代码模板通过issues的方式发布上来 让这个项目越做越完美
https://github.com/fangkyi03/taroTool.git
