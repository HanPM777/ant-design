---
order: 1
title:
  zh-CN: 其他提示类型
  en-US: Other types of message
---

## zh-CN

包括成功、失败、警告。

## en-US

Messages of success, error and warning types.

```jsx
import { message, Button, Space } from 'antd';

const success = () => {
  message.success('This is a success message');
};

const error = () => {
  message.error('网络中断，建议您先检查网络后重试');
};

const warning = () => {
  message.warning('This is a warning message');
};

ReactDOM.render(
  <Space>
    <Button onClick={success}>Success</Button>
    <Button onClick={error}>Error</Button>
    <Button onClick={warning}>Warning</Button>
  </Space>,
  mountNode,
);
```
