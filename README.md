# AlignTextView
字体对齐的textview
  
![截图](./align-text-view-small.png)  
  
###系统要求
Android 4.0以上

### 快速使用
        <cn.androiddevelop.aligntextview.lib.AlignTextView
            android:id="@+id/alignTv"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:textSize="@dimen/small_font" />

### 相关方法
	setAlign(Align align)
设置每一段最后一行对齐方式，默认居左对齐  
  
  
### 使用说明
-  AlignTextView在对齐的时候不会对英文单词等进行考虑，使其连在一起。
-  项目位与app下，可以单独提取出cn.androiddevelop.aligntextview.lib.AlignTextView使用

### 更新历史
####1.1
修正由于对齐造成textview行数减少，从而下方留出空白。