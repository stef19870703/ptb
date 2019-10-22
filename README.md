
		<title>淘宝优惠券</title>
		<style type="text/css">
			table {
				border: 0.5px solid green;
			}
			table tr th{
				border: 0.5px solid green;
			}
			table  tr  td {
				border: 0.5px solid green;
			}
			table  tr  td  span {
				font-size: 2px;
			}
		</style>
	</head>
	<body style="text-align: center;">
		<h3><span style="color: blueviolet;">一定要记得定好9:58的闹钟！</span></h3>
		<table>
			<tr>
				<th style="width: 20%;">抢购时间</th>
				<th style="width: 20%;">品名</th>
				<th style="width: 25%;">活动</th>
				<th style="width: 25%;">价格</th>
				<th style="width: 10%;">链接</th>
			</tr>
			<tr>
				<td><span>10月23日10:00 开抢</span></td>
				<td><span>维达细韧3层130抽24包抽纸</span></td>
				<td><span>前10分钟第2件5折</span></td>
				<td><span>第一件49.9元，第二件24.95元，折合1.56元一包</span></td>
				<td><input id="s1" type="text" style="display: none;" value="$SJ3IYJW5TQD$" /><a href="javascript:copy('s1')"><span>复制链接</span></a></td>
			</tr>
			<tr>
				<td><span>10月23日10:00 开抢</span></td>
				<td><span>洁柔Face3层110抽27包抽纸</span></td>
				<td><span>前10分钟第2件5折</span></td>
				<td><span>第一件63.9元，第二件24.95元，折合1.775元一包</span></td>
				<td><input id="s2" type="text" style="display: none;" value="$6mzRYJWTrzY$" /><a href="javascript:copy('s2')"><span>复制链接</span></a></td>
			</tr>
		</table>
	</body>
	<script language="JavaScript">
		function copy(promotion_input_id) {
			var promotion_input = document.getElementById(promotion_input_id);
			if (navigator.userAgent.match(/(iPhone|iPod|iPad);?/i)) {
				window.getSelection().removeAllRanges();
				var range = document.createRange();
				range.selectNode(promotion_input);
				window.getSelection().addRange(range);
				var successful = document.execCommand('copy');
				window.getSelection().removeAllRanges();
				alert("复制成功，打开手机淘宝即可购买");
			} else {
				promotion_input.select();
				document.execCommand("Copy");
				alert("复制成功，打开手机淘宝即可购买");
			}
		}
	</script>
