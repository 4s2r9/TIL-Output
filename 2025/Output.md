# 0205
blur イベント  
要素がフォーカスを失ったときに発火するイベント   
```html
<input type="text" id="first_name" onblur="check(this)">
```
```js
<script>
  function check(obj){
    if(!obj.value){
      alert("入力してください")
    }
  }  
</script>
```
このように書くだけで input からフォーカスを外すとアラートを出すことができる。  
blur イベントを使うことによって、フォームの入力された内容をクッキーなどに一時保存することが可能ではないかと思った。
