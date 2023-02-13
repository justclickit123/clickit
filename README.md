
<html>
  <head>
    <style>
      body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      
      .container {
        text-align: center;
      }
      
      button {
        background-color: #4CAF50;
        color: white;
        padding: 16px 32px;
        border-radius: 4px;
        border: none;
        outline: none;
        cursor: pointer;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        font-size: 24px;
        margin-top: 40px;
      }
      
      h2 {
        font-size: 36px;
        margin-bottom: 40px;
      }
    </style>
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-1786135172046524"
     crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="container">
      <h2>Click Counter</h2>
      <button id="click-button">CLICK</button>
      <p id="click-count">Number of clicks: 0</p>
    </div>
    
    <script>
      const button = document.getElementById("click-button");
      const countDisplay = document.getElementById("click-count");
      let count = 0;
      
      button.addEventListener("click", function() {
        count += 1;
        countDisplay.innerHTML = `Number of clicks: ${count}`;
      });
    </script>
  </body>
</html>
