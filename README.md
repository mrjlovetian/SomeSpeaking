# 小江江格言
### 我可闭于核桃壳内，而仍将自认为我是个无疆限之君主！
### 冲突的根本原因是资源争夺
### 喜剧或是悲剧的执照者仅仅是个误会罢了！

## 练习

 这是什么东西（======）
 =========
 
 这个呢（---------）
 --------
 




## 标题 
### 哈哈 (###)
#### 哈哈哈 (####)
##### 嘿嘿 (#####)
###### 哦哦 (######)
####### 喵喵 (#######)
######## ad(########)


## 分类 
* red (*)

## 测试
- 消息 (-)
+ message (+)




## OL
<ol>
<li>段落1</li>
<li>段落2</li>
</ol>  （<ol><li>段落1</li><li>段落2</li></ol>）

<p>这样表示一个段落么？这是什么意思啊，搞不明白<p>（<p></p>）

## 代码区块 (<pre><code></code></pre>)
<pre><code> CGFloat normalRed, normalGreen, normalBlue, normalAlpha;
        CGFloat selectedRed, selectedGreen, selectedBlue, selectedAlpha;
        
        [self.itemTitleColor getRed:&normalRed green:&normalGreen blue:&normalBlue alpha:&normalAlpha];
        [self.itemTitleSelectedColor getRed:&selectedRed green:&selectedGreen blue:&selectedBlue alpha:&selectedAlpha];
        // 获取选中和未选中状态的颜色差值
        CGFloat redDiff = selectedRed - normalRed;
        CGFloat greenDiff = selectedGreen - normalGreen;
        CGFloat blueDiff = selectedBlue - normalBlue;
        CGFloat alphaDiff = selectedAlpha - normalAlpha;
        // 根据颜色值的差值和偏移量，设置tabItem的标题颜色
        leftItem.titleLabel.textColor = [UIColor colorWithRed:leftScale * redDiff + normalRed
                                                        green:leftScale * greenDiff + normalGreen
                                                         blue:leftScale * blueDiff + normalBlue
                                                        alpha:leftScale * alphaDiff + normalAlpha];
        rightItem.titleLabel.textColor = [UIColor colorWithRed:rightScale * redDiff + normalRed
                                                         green:rightScale * greenDiff + normalGreen
                                                          blue:rightScale * blueDiff + normalBlue
                                                         alpha:rightScale * alphaDiff + normalAlpha];</code></pre>

 

## 显示图片，添加个美女图片看看 (![Alt text]())
![Alt text](/girl.jpg)


