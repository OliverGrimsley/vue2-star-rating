# vue2-star-rating
A simple Vue 2 component for star ratings that does not rely on any plugins or dependent js.

This vue component is based on [https://github.com/Jamiek94/Vuejs-rating](https://github.com/Jamiek94/Vuejs-rating)

How to Use:  import into your javascript:

```javascript
import showRatings from './components/showRatings.vue';
...
Vue.component('show-ratings',showRatings);
...
var vm = new Vue({
  el: '#employee',
	components: {
    ...,
    showRatings
  }
});
```

Reference the component wherever you need a rating based on stars:
```php
<div id="employee">
  <show-ratings max="10" v-model="question.value"></show-ratings>
</div>
```
