<html>
<head>
<style>
body {
  background-image: url("https://pic.pimg.tw/hamilton29/1378663715-3261696543_n.jpg");
}
</style>
</head>
<body>
<form id="orderForm1" action="http://203.64.84.113/x/RQ_RS.aspx" method="post"  name="form1" >
<h1 style="color:Green;text-align: center;">皮膚科申請預約</h1>
<h4>姓名:</h4>
<input type="text"name="name"><br>
<h4>性別:</h4>
<input type="radio" name="gender" value="male" checked> 男
<input type="radio" name="gender" value="female"> 女<br>
<h4>email:</h4>
<input type="text" id="email" name="email"><br>
<h4>電話:</h4>
<input type="text" id="phone" name="phone"><br>
<h4>選擇日期</h4>
<select id="date" name="date">
<option value="mon"selected>星期一</option>
<option value="tue">星期二</option>
<option value="wed">星期三</option>
<option value="thu">星期四</option>
<option value="fri">星期五</option>
</select>
<h4>選擇時間</h4>
<select id="time" name="time">
<option value="am"selected>早上</option>
<option value="af">下午</option>
<option value="pm">晚上</option>
</select>
<h4>選擇類型</h4>
<select id="detype" name="detype">
<option value="de"selected>醫學皮膚病學</option>
<option value="cos">化妝品皮膚病學</option>
<option value="jun">初級衛生保健</option>
</select><br><br>
<textarea name="suggest">Questions/Comments</textarea>
<input type="submit" value="確認送出">
</form>
</body>
</html>
