# Keyboard
MODEL : K01 made by 'HTML' & 'CSS'
You need to copy the HTML and CSS code below and paste it into the 'CODEPIN' and run the code


1)HTML :

<div class="container">
  <div class="row">
    <div class="btn">1</div>
    <div class="btn">2</div>
    <div class="btn">2</div>
    <div class="btn">3</div>
    <div class="btn">4</div>
    <div class="btn">5</div>
    <div class="btn">6</div>
    <div class="btn">7</div>
    <div class="btn">8</div>
    <div class="btn">9</div>
    <div class="btn">0</div>
    <div class="btn">=</div>
    <div class="btn">-</div>
    <div class="btn up_key">UP</div>
    <div class="btn backspace_key">Backspace</div>
  </div>

  <div class="row">
    <div class="btn tab_key">Tab</div>
    <div class="btn">(</div>
    <div class="btn">)</div>
    <div class="btn">!</div>
    <div class="btn">@</div>
    <div class="btn">#</div>
    <div class="btn">*</div>
    <div class="btn">&</div>
    <div class="btn">{</div>
    <div class="btn">}</div>
    <div class="btn">[</div>
    <div class="btn">]</div>
    <div class="btn">+</div>
    <div class="btn">DW</div>
    <div class="btn">/</div>
    <div class="btn">F</div>

  </div>
  <div class="row">
    <div class="btn capslock_key=">Caps Lock</div>
    <div class="btn">Q</div>
    <div class="btn">W</div>
    <div class="btn">E</div>
    <div class="btn">R</div>
    <div class="btn">T</div>
    <div class="btn">Y</div>
    <div class="btn">U</div>
    <div class="btn">I</div>
    <div class="btn">O</div>
    <div class="btn">P</div>
    <div class="btn">A</div>
    <div class="btn">S</div>
    <div class="btn">D</div>
    <div class="btn">ET</div>
    <div class="btn enter_key">Enter</div>

  </div>
  <div class="row">
    <div class="btn shift_key">Shift</div>
    <div class="btn">G</div>
    <div class="btn">H</div>
    <div class="btn">J</div>
    <div class="btn">K</div>
    <div class="btn">L</div>
    <div class="btn">Z</div>
    <div class="btn">X</div>
    <div class="btn">C</div>
    <div class="btn">V</div>
    <div class="btn">B</div>
    <div class="btn">N</div>
    <div class="btn">M</div>
    <div class="btn">V</div>
    <div class="btn">WS</div>
    <div class="btn shift_key">Shift</div>

  </div>
  <div class="row">
    <div class="btn ctrl_key">Ctrl</div>
    <div class="btn">Win</div>
    <div class="btn">Alt</div>
    <div class="btn space_key">Space</div>
    <div class="btn">.</div>
    <div class="btn">?</div>
    <div class="btn"><</div>
        <div class="btn">></div>
        <div class="btn ctrl_key">Ctrl</div>

    </div>
  </div>

  2)css : 
  
* {
  margin: center;
  padding: 0;
  box-sizing: border-box;
  font-family: roboto;
  user-select: none;
}
body {
  background-color: #151313;
  display: flex;
  align-items: center;
  justify-content: center;
  min-hight: 100vh;
}
.container {
  width: 650px;
  height: 230px;
  box-shadow: -3px 3px 5px red, 3px -3px 5px red;
  border-radius: 20px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 25px 0;
}
.container .row {
  display: flex;
}

.btn {
  width: 30px;
  height: 30px;
  border: 0;
  color: red;
  border-radius: 4px;
  font-wight: bold;
  font-size: 12px;
  margin: 4px;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
}
.backspace_key {
  width: 70px;
}
.tab_key {
  width: 48px;
}
.space_key {
  width: 300px;
}
.up_key {
  width: 40px;
}
.dw_key {
  width: 20px;
}

.btn.active {
  box-shadow: -2px -2px 4px red, 2px 2px 4px red;
}
.btn:active {
  box-shadow: -2px -2px 4px red, 2px 2px 4px red;
}


  
