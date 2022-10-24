# MomentsAgo VueJs 3 Single File Component
No dependencies, just component that renders string which says how much time has passed since date you provided as parameter.

## How to use it

Copy *MomentsAgo.vue* where you store reuseable components.

```vue
<template>
    ...
    <span>
        <MomentsAgo :date="date" />
    </span>
    ...
</template>

<script>
import MomentsAgo from '../  your dir  /MomentsAgo.vue'

export default{
    ...
    components: { MomentsAgo },

    data(){
        date: new Date()
    }
    ...
}
</script>
```

## More info
Inside */example/MomentsAgoExample.vue* you can read more on how it works, extending feature and see examples, just import both components properly. 