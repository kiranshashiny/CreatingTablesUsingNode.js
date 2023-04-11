# CreatingTablesUsingNode.js


```
$ cat build.html
  <html>
    <head>

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.4.4/jquery.js"></script>
<script type="text/javascript">

$(document).ready(function(){
    $('#table_id td.y_n').each(function(){
        if ($(this).text() == 'Sell') {
            $(this).css('background-color','#f00');
        }

        if ($(this).text() == 'Buy') {
            $(this).css('background-color','lightgreen');
        }
    });
});
</script>

      <style>
        table {
          width: 100%;
        }
        tr {
          text-align: left;
          border: 1px solid black;
        }
        th {
          background: #f1f1c1; 
	}
        td {
          padding: 15px;
        }
        tr:nth-child(odd) {
          background: #FC9
        }
        tr:nth-child(even) {
          background: #FC9
        }
        .no-content {
          background-color: red;
        }
      </style>
    </head>
    <body>
      
  <table id="table_id">
    <tr>
        <th>Date</td>
        <th>Ticker </td>
        <th>Symbol Name</td>
        <th>Price</td>
        <th>Date</td>
        <th>Zacks Rank</td>
    </tr>
    
  <tr>
    <td>1</td>
    <td>MSFT</td>
    <td>Microsoft</td>
    <td>289</td>
    <td>04/04/23</td>
    <td class="y_n">Sell</td>
  </tr>

  <tr>
    <td>2</td>
    <td>MSFT</td>
    <td>Microsoft</td>
    <td>285</td>
    <td>04/06/23</td>
    <td class="y_n">Buy</td>
  </tr>

  </table>
  <br>
  <br>

  <table id="table_id">
    <tr>
        <th>Date</td>
        <th>Ticker </td>
        <th>Symbol Name</td>
        <th>Price</td>
        <th>Date</td>
        <th>Zacks Rank</td>
    </tr>
    
    <tr>
    <td>1</td>
    <td>AAPL</td>
    <td>Apple</td>
    <td>162</td>
    <td>04/04/23</td>
    <td class="y_n">Sell</td>
    </tr>
  </table>



  <br>
  <br>

  <table id="table_id">
    <tr>
        <th>Date</td>
        <th>Ticker </td>
        <th>Symbol Name</td>
        <th>Price</td>
        <th>Date</td>
        <th>Zacks Rank</td>
    </tr>
    
    <tr>
    <td>1</td>
    <td>NVDA</td>
    <td>Nvidia</td>
    <td>275</td>
    <td>04/04/23</td>
    <td class="y_n">Strong Buy</td>
    </tr>
  </table>


    </body>
  </html>
  
  
  ```
