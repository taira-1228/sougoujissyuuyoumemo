- コードは以下の通り
```
<%@ page language="java" contentType="text/html; charset=UTF-8"
	pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>患者登録</title>
<%@include file="/css/main.css" %><!-- ここでcssを呼び出す -->
</head>
<body>
	<input type="submit" value="メインメニューへ" onclick="">
	<div class="inputSpace">
		姓<input type="text" id="fname">
		名<input type="text" id="lname">
		せい<input type="text" id="yfname">
		めい<input type="text"id="ylname">
		<input type="submit" value="登録" onclick="addPatientInfomation.js">
	</div>
</body>
</html>
```
