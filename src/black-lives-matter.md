
# Black lives matter
[Checkout challenge here](https://cssbattle.dev/play/54)

<img src="https://i.ibb.co/jhqSVkp/Screenshot-2022-03-03-at-5-51-27-PM.png" alt="Screenshot-2022-03-03-at-5-51-27-PM" width="280" height="280">

![Image jpeg](https://i.ibb.co/jhqSVkp/Screenshot-2022-03-03-at-5-51-27-PM.png)

```html
<div class="palm">
  <div class="thumb"></div>
 <div class="fingers-container">
   <div class="finger finger-1"></div>
   <div class="finger finger-2"></div>
   <div class="finger"></div>
   <div class="finger finger-4"></div>
 </div>
</div>
<div class="wrist"></div>
<style>
  body {
    height: 100%;
    background: #F9E492;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column
}
  .palm {
    position: relative;
    background: #191919;
    width: 100px;
    height: 101px;
    border-radius: 10px
  }
  .wrist {
    background: #191919;
    width: 50px;
    height: 45px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px
  }
  .fingers-container {
    background: #F9E492;
    height: 61;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    
  }
  .finger {
    width: 20%;
    margin-bottom: 5px;
    border-radius: 10px;
    height: 45px;
    background: #191919;
  }
  .finger-2 {
    height: 55px;
  }
  .finger-4 {
    height: 35px;
  }
  .finger-1 {
    margin-left: 5px;
  }
  .thumb {
    position: absolute;
    width: 20px;
    height: 65px;
    background: #191919;
    border: 5px solid #F9E492;
    border-radius: 15px;
    top: 28;
    left: 2;
    transform: rotate(60deg)
  }
</style>
```
