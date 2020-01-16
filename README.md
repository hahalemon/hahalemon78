
<!DOCTYPE html>
<html>
<head>

<style>
* {box-sizing: border-box;}
ul {list-style-type: none;}
body {font-family: Verdana, sans-serif;}

.month {
    padding: 25px 25px;
    width: 100%;
    background: #1abc9c;
    text-align: center;
    color: white;
    font-size: 20px;
}


.weekdays {
    margin: 0;
    padding: 10px 0;
    background-color: #ddd;
}

.weekdays li {
    display: inline-block;
    width: 13.6%;
    color: #572;
    text-align: center;
}

.days {
    padding: 10px 0;
    background: #eee;
    margin: 0;

}

.days li {
    list-style-type: none;
    display: inline-block;
    width: 13.6%;
    text-align: center;
    margin-bottom: 5px;
    font-size:12px;
    color: #777;
	
}

.days li .active {
    padding: 5px;
	background: #1abc9c;
    color: white !important
}

a:hover { 
    background-color: yellow;
}

a:link {text-decoration:  none;
  
}

/* Add media queries for smaller screens */
@media screen and (max-width:720px) {
    .weekdays li, .days li {width: 13.1%;}
}

@media screen and (max-width: 420px) {
    .weekdays li, .days li {width: 12.5%;}
    .days li .active {padding: 2px;}
}

@media screen and (max-width: 290px) {
    .weekdays li, .days li {width: 12.2%;}
}
</style>
</head>
<body>

<h1>start of break from Miami</h1>

<div class="month">      
      <span> Dec 2019</span>
</div>

<ul class="weekdays">
  <li>Su</li>  
  <li>Mo</li>
  <li>Tu</li>
  <li>We</li>
  <li>Th</li>
  <li>Fr</li>
  <li>Sa</li>
</ul>

<ul class="days">  
  <li> </li>
  <li> </li>
  <li>1</li>
  <li>2</li>
  <li>3</li>
  <li>4</li>
  <li>5</li>
  <li>6</li>
  <li>7</li>
  <li> 8 </li>
  <li>9</li>
  <li>10</li>
  <li>11</li>
  <li>12</li>
  <li>13</li>
  <li>14</li>
  <li>15</li>
  <li>16</li>
  <li>17</li>
  <li>18</li>
  <li>19</li>
  <li>20</li>
  <li>21</li>
  <li>22</li>
  <li>23</li>
  <li>24</li>
  <li>25</li>
  <li>26</li>
  <li>27</li>
  <li><mark><span class="active"><a href=" https://www.hellofresh.com/landing/holidays"</span> 28</a></mark></li>
    <li><mark>29</mark></li>
    <li><mark>30</mark></li>
    <li><mark>31</mark></li>
</ul>

</body>
</html>
