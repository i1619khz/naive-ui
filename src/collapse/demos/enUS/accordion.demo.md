# Accordion

Like an accordion.

```html
<n-collapse v-model:expandedNames="activeNames" accordion>
  <n-collapse-item title="right" name="1">
    <div>good</div>
  </n-collapse-item>
  <n-collapse-item title="right" name="2">
    <div>good</div>
  </n-collapse-item>
</n-collapse>
```

```js
export default {
  data () {
    return {
      activeNames: []
    }
  }
}
```