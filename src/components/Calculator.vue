<template>
  <div id="calcContainer">
     <input id="user_input" placeholder="0">
      <br>
      <button class="btn" onclick="press(1)">1</button>
      <button class="btn" onclick="press(2)">2</button>
      <button class="btn" onclick="press(3)">3</button>
      <button style="background:#ffb84d;" class="btn" onclick="press('+')">+</button>
      <br>
      <button class="btn" onclick="press(4)">4</button>
      <button class="btn" onclick="press(5)">5</button>
      <button class="btn" onclick="press(6)">6</button>
      <button style="background: #ffcc80;" class="btn" onclick="press('-')">-</button>
      <br>
      <button class="btn" onclick="press(7)">7</button>
      <button class="btn" onclick="press(8)">8</button>
      <button class="btn" onclick="press(9)">9</button>
      <button style="background: #ffe0b3;" class="btn" onclick="press('*')">*</button>
      <br>
      <button class="btn" onclick="press('.')">.</button>
      <button class="btn" onclick="press(0)">0</button>
      <button class="btn" onclick="erase()">C</button>
      <button style="background: #fff5e6;" class="btn" onclick="press('/')">/</button>
      <br>
      <button class="btnEqual" onclick="equal()">=</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  // props: {
  //   msg: String
  // }
}
</script>
<style>
#calcContainer {
  width: 370px;
    margin: auto;
    border-radius: 2px;
    background-color: #f2f2f2;
    padding: 15px 25px 15px 20px;
    box-shadow: 0px 2px 4px 0px rgb(0 0 0 / 50%);
}
.btn {
  width: 24%;
    height: 45px;
 
    border: none;
    outline: none;
    margin-top: 3px;

}
#user_input {
margin-top: 10px;
margin-bottom: 10px;
border: none;
width: 100%;
}
</style>
