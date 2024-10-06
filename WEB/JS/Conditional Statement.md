# 조건문의 활용

```html
 <input
      id="night_day"
      type="button"
      value="night"
      onclick="
        if(document.querySelector('#night_day').value === 'night') { 
          document.querySelector('body').style.backgroundColor = 'black';
          document.querySelector('body').style.color = 'white';
          document.querySelector('#night_day').value = 'day';
        } else {
          document.querySelector('body').style.backgroundColor = 'white';
          document.querySelector('body').style.color = 'black';
          document.querySelector('#night_day').value = 'night';
        }
      "
    />
```
<br>

> ===
- 좌항과 우항의 관계에 따라 true / false 중 하나의 값을 만들어내는 연산자
