# polarplot with zoom
d3.js based polarplot with zoom capability

## Steps to integrate:
* Add Java script files to the project

        <p>
          <script src="https://d3js.org/d3.v3.min.js"></script>
          <script src="polarPlotZoom.js"></script>
        </p>

* Add div tag

  <div>
      <input type="radio" name="pattern" value="1" onclick="getColor(this.value)" checked> <span style= "color: red">Red</span><br>
       <input type="radio" name="pattern" value="2" onclick="getColor(this.value)"> <span style= "color: green" >Green</span><br>
      <br>
  </div>
  <button id="zoom_in">+</button>
  <button id="zoom_out">-</button>
  <button id="zoom_init"> Init</button>
  <button id="stop-brush"> sb</button>
  <div id="div_svg"></div>

![Image](polarPlotBeforeZoomBrush.jpeg)

![Image](polarPlotAfterZoomBrush.jpeg)

[Sample project](https://codepen.io/bsrvasulu/pen/YjoBvN)
