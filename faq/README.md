# 常见问题 {#faq}

* <strong class="question"><span class='q-icon'><i class="fa fa-question" aria-hidden="true"></i></span>问：</strong>
  页面锚点如何导航

  <strong class="answer">答：</strong>

  『方案一』：为锚点添加点击事件
  ```js
  scrollToAnchor = (anchorName) => {
      if(anchorName) {
        let anchorEle = document.getElementById(anchorName);
        if(anchorEle) {
          anchorEle.scrollIntoView();
        }
      }
    }
  ```
  添加点击
  ```html
  <a onClick={()=> scrollToAnchor(name)}>click me </a>
  ```
