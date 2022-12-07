# Shopify Polaris DateTime Picker

##  Installation
```
npm i shopify-polaris-datetime-picker
```

(Yarn)
```
yarn add shopify-polaris-datetime-picker
```

## Usage
1. Import the component
```
// es6
import DateTimePicker from "shopify-polaris-datetime-picker";

//es5
const DateTimePicker = require("shopify-polaris-datetime-picker");
```

2. Use it
```
const SomeComponent = () => {
  // ...
  return (
    // ...
    <DateTimePicker {...props} />
  );
};
```

## Props
| Prop Name    | Type     | Description                                                     | Required | Default    |
|--------------|----------|-----------------------------------------------------------------|----------|------------|
| initialValue | Number   | UNIX timestamp in milliseconds                                  | false    | Date.now() |
| dateLabel    | String   | Label of date input                                             | false    | "Date"     |
| timeLabel    | String   | Label of time input                                             | false    | "Time"     |
| onChange     | Function | Called for datetime changed Returns Date object of new datetime | false    | () => {}   |