<html>
  <head>
    <title>Title of the document</title>
    <style>
      .content {
        overflow: auto;
        border: 3px solid #666;
      }
      .content div {
        padding: 10px;
      }
      .content a {
        color: darkblue;
      }
      .blue {
        float: right;
        width: 45%;
        background-color: #1faadb;
      }
      .green {
        float: left;
        width: 35%;
        background-color: #8ebf42;
      }
    </style>
  </head>
  <body>
    <div class="content">
      <div class="blue">
        <p>This is some paragraph inside div tag.</p>
        <a href="#">This is some hyperlink inside div tag.</a>
        <ul>
          <li>List item 1</li>
          <li>List item 2</li>
        </ul>
      </div>
      <div class="green">
        <p>This is some paragraph inside div tag.</p>
        <ol>
          <li>List item 1</li>
          <li>List item 2</li>
        </ol>
      </div>
    </div>
  </body>
</html>
