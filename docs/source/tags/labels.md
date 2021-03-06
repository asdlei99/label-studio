---
title: Labels
type: tags
order: 403
---

Labels tag, create a group of labels

### Parameters

-   `name` **[string]** name of the element
-   `toName` **[string]** name of the element that you want to label
-   `choice` **(single | multiple)** configure if you can select just one or multiple labels (optional, default `single`)
-   `showInline` **[boolean]** show items in the same visual line (optional, default `false`)

### Examples

```html
<View>
  <Labels name="type" toName="txt-1">
    <Label alias="B" value="Brand"></Label>
    <Label alias="P" value="Product"></Label>
  </Labels>
  <Text name="txt-1" value="$text"></Text>
</View>
```
