# 字数限制

惜字如金。

```html
<n-space vertical>
  <n-input maxlength="30" show-count clearable />
  <n-input type="textarea" maxlength="30" show-count />
  <n-input type="textarea" default-value="啥" show-count #count="{ value }">
    {{ value.includes('啥') ? '99+' : value.length }}
  </n-input>
</n-space>
```
