# vue2-flip-countdown

A simple flip countdown timer component for Vue 2.x

![screenshot](https://raw.githubusercontent.com/philipjkim/vue2-flip-countdown/master/screnshot.png "vue2-flip-countdown")

## Installation

```
npm i vue2-flip-countdown --save
```

## Usage

```vue
<template>
  <div>
    <flip-countdown deadline="2018-12-25 00:00:00"></flip-countdown>
  </div>
</template>

<script>
  import FlipCountdown from 'vue2-flip-countdown'

  export default {
      components: { FlipCountdown }
  }
</script>
```

# References

- [vuejs-countdown](https://github.com/getanwar/vuejs-countdown)
- [Demo for 'Flip clock & countdown, Vue'](https://codepen.io/shshaw/pen/BzObXp)