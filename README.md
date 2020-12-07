简历网站：https://yuyanghyy.github.io/cv/

browser-sync监听所有文件 browser-sync start --server --files "**/**.*"


## 简历（响应式web版、psd版）


#### 打印方法

> chrome浏览器 - "打印" - 设置无边距 - 即可导出


#### 修改方法
1. 编辑`index.html`
2. 如需修改技能状态条，可在`scss/style.scss`里面编辑
```
//例如html状态条比例(使用flex布局中的比例)
.i-html {
     .in {flex: 8;}//.in为绿色部分比例
     .out {flex: 2;}//.out为灰色部分比例
        }
```
3. 修改完浏览器预览-打印

2020.12.7 修改完成后，如何更新github.io网站
-修改完成后会自动变更
-在对应的repo里面，setting->Github Pages查看
