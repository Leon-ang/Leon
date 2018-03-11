# Leon
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<script type="text/javascript">
			window.onload = function(){
			var at = document.getElementById("tj1");
			var at1 = document.getElementById("tj2");
			var at2 = document.getElementById("tj3");
			var at3 = document.getElementById("tj");
			at.onclick = function(){
				alert("想删除，做梦吧！O(∩_∩)O哈哈~");
				
			}
			at1.onclick = function(){
				alert("想删除，做梦吧！O(∩_∩)O哈哈~");
				
			}
			at2.onclick = function(){
				alert("想删除，做梦吧！O(∩_∩)O哈哈~");
				
			}
			at3.onclick = function(){
				alert("输入错误请从新输入···");
				
			}
	}
		</script>
	</head>
	<body>
		<table id="b1">
			<tr>
				<td>姓名：</td>
				<td>性别：</td>
				<td>年龄：</td>
				<td></td>
			</tr>
			<tr>
				<td>老王</td>
				<td>女</td>
				<td>二十</td>
				<td><button id="tj1" type="submit"  value="asd">删除</button></td>
			</tr>
			<tr>
				<td>老马</td>
				<td>女</td>
				<td>二十</td>
				<td><button id="tj2" type="submit"  value="asd">删除</button></td>
			</tr>
			<tr>
				<td>老蒋</td>
				<td>女</td>
				<td>二十</td>
				<td><button id="tj3" type="submit"  value="asd">删除</button></td>
			</tr>
		</table>
		<div id="zj">
			<h3>添加新成员信息</h3>
			<table>
				<tr>
					<td>姓名：</td>
					<td><input type="text" name="Name" id="Name"/></td>
				</tr>
				<br />
				<tr>
					<td>性别：</td>
					<td><input type="text" name="Gender" id="Gender"/></td>
				</tr>
				<br />
				<tr>
					<td>年龄：</td>
					<td><input type="text" name="Age" id="Age"/></td>
				</tr>
				<br />
				<tr>
					<td colspan="2" align="center"><button type="submit" id="tj" value="asd">提交</button></td>
				</tr>
			</table>
		</div>
	</body>
</html>
