用`Accordion`组件定义折叠块，用于切换内容，默认打开，再次点击会隐藏内容。折叠块内容遵循 Markdown 语法。

## 示例效果

<Accordion title="折叠块" >
  这里是折叠块里的内容.点击可实现收缩.
</Accordion>

#### 代码
```
<Accordion title="折叠块" >
  这里是折叠块里的内容.点击可实现收缩.
</Accordion>
```
### 设置默认收起

<Accordion title="默认收起折叠块" defaultOpen={false}>
  这里是折叠块里的内容.默认关闭.
</Accordion>

#### 代码
```
<Accordion title="默认收起折叠块" defaultOpen={false}>
  这里是折叠块里的内容.默认关闭.
</Accordion>
```

### 添加图标

<Accordion title="设置图标" icon="material-two-tone-storefront">
  为折叠块引入图标.
</Accordion>

#### 代码
```
<Accordion title="添加图标" icon="material-two-tone-storefront">
  为折叠块引入图标.
</Accordion>
```
## 参数说明
<DataSchema id="96036360" />