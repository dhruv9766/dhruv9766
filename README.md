<html lang="pt">
	<head>
		<title>Dhruv Patel</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
		<link
			rel="stylesheet"
			href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
			integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk"
			crossorigin="anonymous"
		/>
		<link
			href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@200;400;700&display=swap"
			rel="stylesheet"
		/>
		<style>
			* {
				font-family: 'Roboto Slab', serif;
			}
			.show-on-mobile {
				display: none;
				width: 100%;
				background: #ffffff;
				padding: 20px;
				margin-bottom: 25px;
			}
			.wrapper {
				display: flex;
				align-items: center;
				justify-content: center;
				flex: 1;
				height: 100vh;
				overflow-x: hidden;
			}
			.wrapper .main-form {
				display: flex;
				align-items: center;
				justify-content: space-evenly;
				flex-direction: column;
				flex: 1;
				height: 100%;
				padding: 15px;
			}
			.wrapper .main-form form {
				width: 80%;
			}
			.wrapper .main-form form .split-size {
				width: 100%;
				display: flex;
				align-items: flex-start;
				justify-content: space-between;
			}
			.wrapper .main-form form .split-size .form-group {
				width: 49%;
			}
			.wrapper .caption-area {
				display: flex;
				align-items: center;
				justify-content: center;
				flex: 1;
				background: #ffffff url(https://i.imgur.com/5ZybQHM.png) no-repeat 100% 100% / contain;
				height: 100%;
				padding: 15px;
				position: relative;
			}
			.wrapper .caption-area .logo img {
				position: absolute;
				right: 50%;
				top: 25px;
				width: 35%;
				transform: translateX(50%);
			}
			.btn-primary {
				background-color: #161de9;
				border-color: #161de9;
			}
			.btn-primary:hover {
				background-color: #3ADF00;
				border-color: #3ADF00;
			}
			@media (max-width: 1000px) {
				.wrapper .main-form form {
					width: 90%;
				}
				.wrapper .main-form {
					overflow-y: scroll;
				}
				.wrapper .caption-area {
					background: #003087 url(https://i.imgur.com/5ZybQHM.png) no-repeat 100% 100% / cover;
				}
				.wrapper .caption-area .logo img {
					width: 55%;
				}
				.wrapper .main-form form .split-size {
					flex-direction: column;
				}
				.wrapper .main-form form .split-size .form-group {
					width: 100%;
				}
			}
			@media (max-width: 850px) {
				.wrapper {
					height: auto;
				}
				.show-on-mobile {
					display: flex;
					align-items: center;
					justify-content: center;
					width: 100%;
				}
				.show-on-mobile img {
					width: 45%;
				}
				.wrapper .main-form {
					width: 100%;
					flex: initial;
				}
				.wrapper .caption-area {
					display: none;
				}
				.wrapper .main-form {
					background: #ffffff;
				}
				.wrapper .main-form form {
					width: 80%;
					background: #ffffff;
					padding: 20px;
					-webkit-box-shadow: 0px 0px 5px 0px rgba(0, 0, 0, 0.15);
					-moz-box-shadow: 0px 0px 5px 0px rgba(0, 0, 0, 0.15);
					box-shadow: 0px 0px 15px 0px rgba(0, 0, 0, 0.15);
					border-radius: 10px;
				}
				.wrapper .main-form form .split-size {
					flex-direction: initial;
				}
				.wrapper .main-form form .split-size .form-group {
					width: 49%;
				}
			}
			@media (max-width: 580px) {
				.wrapper .main-form form {
					width: 90%;
				}
				.wrapper .main-form {
					overflow-y: scroll;
				}
				.wrapper .main-form form .split-size {
					flex-direction: column;
				}
				.wrapper .main-form form .split-size .form-group {
					width: 100%;
				}
			}
		</style>
	</head>

	<body>
		<div class="wrapper">
			<div class="main-form">
				<form>
					<div class="form-group">
						<label class="control-label" for="active">Dhruv Patel:</label>

						<label class="control-label" for="active">Dhruv Patel </label>
						<select class="form-control" name="cbAtivo" id="cbAtivo">
							<option value="0" selected="">All ASSETS</option>
						<option value="AUD_CAD">AUD_CAD</option>
        <option value="AUD_CHF">AUD_CHF</option>
        <option value="AUD_JPY">AUD_JPY</option>
        <option value="AUD_USD">AUD_USD</option>
        <option value="CAD_JPY">CAD_JPY</option>
        <option value="EUR_AUD">EUR_AUD</option>
        <option value="EUR_CAD">EUR_CAD</option>
        <option value="EUR_CHF">EUR_CHF</option>
        <option value="EUR_GBP">EUR_GBP</option>
        <option value="EUR_JPY">EUR_JPY</option>
        <option value="EUR_NZD">EUR_NZD</option>
        <option value="EUR_USD">EUR_USD</option>
        <option value="EUR_MXN">EUR_MXN</option>
        <option value="GBP_AUD">GBP_AUD</option>
        <option value="GBP_CAD">GBP_CAD</option>
        <option value="GBP_CHF">GBP_CHF</option>
        <option value="GBP_JPY">GBP_JPY</option>
        <option value="GBP_NZD">GBP_NZD</option>
        <option value="GBP_USD">GBP_USD</option>
        <option value="NZD_CHF">NZD_CHF</option>
        <option value="NZD_USD">NZD_USD</option>
        <option value="USD_CAD">USD_CAD</option>
        <option value="USD_CHF">USD_CHF</option> 
        <option value="USD_JPY">USD_JPY</option>
        <option value="USD_INR">USD_INR</option>
        <option value="USD_DKK">USD_DKK</option>
        <option value="USD_NOK">USD_NOK</option>
        <option value="XAU_USD">XAU_USD _ GOLD</option>
        <option value="XAG_USD">XAG_USD _ SILVAR</option>
        <option value="BTC_USD">BTC_USD _ BITCOIN</option>
						</select>
					</div>
					<div class="split-size">
						<div class="form-group">
							<label class="control-label" for="active">Minimum Percentage:</label>
							<select class="form-control" name="minutos_offset" id="selPercentageMin">
								<option value="0" selected> Select Minimum Percentage</option>
								<option value="90">90%</option
								><option value="91">91%</option
								><option value="92">92%</option
								><option value="93">93%</option
								><option value="94">94%</option
								><option value="95">95%</option
								><option value="96">96%</option
								><option value="97">97%</option
								><option value="98">98%</option
								><option value="99">99%</option
								><option value="100">100%</option>
							</select>
						</div>
						<div class="form-group">
							<label class="control-label" for="active">Maximum Percentage:</label>
							<select class="form-control" name="minutos_offset" id="selPercentageMax">
								<option value="0" selected> Select Maximum Percentage</option>
							    <option value="90">90%</option
								><option value="91">91%</option
								><option value="92">92%</option
								><option value="93">93%</option
								><option value="94">94%</option
								><option value="95">95%</option
								><option value="96">96%</option
								><option value="97">97%</option
								><option value="98">98%</option
								><option value="99">99%</option
								><option value="100">100%</option>
							</select>
						</div>
					</div>
					<div class="split-size">
						<div class="form-group">
							<label class="control-label" for="active">Expiration Time :</label>
							<select class="form-control" name="cbTimeFrame" id="selCandleTime"
							><option value="0" selected=""> Select Candle Time</option>
								><option value="M1">M1</option>
								<option value="M4">M2</option>
								><option value="M5">M5</option>
								<option value="M15">M15</option
								><option value="M30">M30</option
								><option value="H1">H1</option
								><option value="H2">H2</option
								><option value="H4">H4</option>
							</select>
						</div>
						<div class="form-group">
							<label class="control-label" for="active">Days to be analyzed:</label>
							<select class="form-control" name="Values ​​To Check" id="selDays">
								 <option value="0" selected> Select Days</option>
								 <option value="01">01</option
								><option value="02">02</option
								><option value="03">03</option
								><option value="04">04</option
								><option value="05">05</option
								><option value="06">06</option
								><option value="07">07</option
								><option value="08">08</option
								><option value="09">09</option
								><option value="10">10</option
								><option value="11">11</option
								><option value="12">12</option
								><option value="13">13</option
								><option value="14">14</option
								><option value="15">15</option
								><option value="16">16</option
								><option value="17">17</option
								><option value="18">18</option
								><option value="19">19</option
								><option value="20">20</option
								><option value="21">21</option
								><option value="22">22</option
								><option value="23">23</option
								><option value="24">24</option
								><option value="25">25</option
								><option value="26">26</option
								><option value="27">27</option
								><option value="28">28</option
								><option value="29">29</option
								><option value="30">30</option
								><option value="31">31</option
								><option value="32">32</option
								><option value="33">33</option
								><option value="34">34</option
								><option value="35">35</option
								><option value="36">36</option
								><option value="37">37</option
								><option value="38">38</option
								><option value="39">39</option
								><option value="40">40</option
								><option value="41">41</option
								><option value="42">42</option
								><option value="43">43</option
								><option value="44">44</option
								><option value="45">45</option
								><option value="46">46</option
								><option value="47">47</option
								><option value="48">48</option
								><option value="49">49</option
								><option value="50">50</option
								><option value="51">51</option
								><option value="52">52</option
								><option value="53">53</option
								><option value="54">54</option
								><option value="55">55</option
								><option value="56">56</option
								><option value="57">57</option
								><option value="58">58</option
								><option value="59">59</option
								><option value="60">60</option
								><option value="61">61</option
								><option value="62">62</option
								><option value="63">63</option
								><option value="64">64</option
								><option value="65">65</option
								><option value="66">66</option
								><option value="67">67</option
								><option value="68">68</option
								><option value="69">69</option
								><option value="70">70</option
								><option value="71">71</option
								><option value="72">72</option
								><option value="73">73</option
								><option value="74">74</option
								><option value="75">75</option
								><option value="76">76</option
								><option value="77">77</option
								><option value="78">78</option
								><option value="79">79</option
								><option value="80">80</option
								><option value="81">81</option
								><option value="82">82</option
								><option value="83">83</option
								><option value="84">84</option
								><option value="85">85</option
								><option value="86">86</option
								><option value="87">87</option
								><option value="88">88</option
								><option value="89">89</option
								><option value="90">90</option
								><option value="91">91</option
								><option value="92">92</option
								><option value="93">93</option
								><option value="94">94</option
								><option value="95">95</option
								><option value="96">96</option
								><option value="97">97</option
								><option value="98">98</option
								><option value="99">99</option
								><option value="100">100</option>
					</select>
					</div>
					</div>
					
					<label class="control-label" for="active">THANK YOU FOR USING MY SIGNALS
©Dhruv Patel©</label>



					<label class="control-label" for="active">USE it is totally FREE  </label>
					<center><b><h5><tt><a href="https://t.me/futuresignala"target="_blank">JOIN @panther_binary_trader </a></h5></b></center></tt>
					<center><i><h6> <a href="https://t.me/extraders"target="_blank">   </a></h6></i></center>
					<center><i><h6> <a href="https://t.me/mirs65"target="_blank">  </a></h6></i></center>
					<center><h2><tt> "  "</center>
					
					</div>
					</div>
					<div class="form-group">
						<label class="control-label" for="active">Ticket Type:</label>
						<select class="form-control" name="cbTimeFrame" id="selOrderType">
							<option value="CALL">CALL</option
							><option value="PUT">PUT</option>
						</select>
					</div>
					<button type="button" onclick="getHistoric()" class="btn btn-primary btn-lg btn-block">
						Generate Signals
					</button>
				</form>
			</div>
		</div>
		<label class="control-label" for="active"> <center> <b> <i>  </i></b></center>
			<center><h4>   </h4></center>
		<!-- Script import -->
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
		<script
			src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
			integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
			crossorigin="anonymous"
		></script>
		<script
			src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"
			integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI"
			crossorigin="anonymous"
		></script>

		<script>
			hoje = new Date();

			dia = hoje.getDate() + 0;

			dias = hoje.getDay() + 1;

			mes = hoje.getMonth() + 1;

			ano = hoje.getYear();

			var listBestPairTimes = [];
			var listPairs = [
				  "EUR_USD",
 
 "GBP_AUD",
 "EUR_AUD",
 "EUR_JPY",
 "GBP_CAD",
 "USD_JPY",
 "EUR_CHF",
 "AUD_CAD",
 "GBP_CHF",
 "EUR_GBP",
 "AUD_CHF",
 "CAD_JPY",
 "GBP_JPY",
 "EUR_CAD",
 "AUD_JPY",
 "GBP_NZD",
			];

			var percentageMin = 100;
			var percentageMax = 100;
			var candleTime = 'M5';
			var daysAnalyse = 20;
			var martingales = 0;
			var orderType = 'PUT';
			var timeInit = 2;
			var timeEnd = 18;

			var requestNumber = 0;
			//First action when clicking on PROCESS DATA button
			function getHistoric() {
				$('body').css('cursor', 'progress');
				listBestPairTimes = [];
				getParameter();
				//I check if the Asset field is in All Assets if not it searches for the selected asset
				if (cbAtivo == 0) {
					requestNumber = listPairs.length;
				} else {
					listPairs = [cbAtivo];
					requestNumber = listPairs.length;
				}

				var count = CalculateCountCandles();
				if (count > 50000) {
					alert('The number of candles exceeds 50,000, please decrease the number of days analyzed');
					return;
				}

				for (var i = 0; i < listPairs.length; i++) {
					var currentPair = listPairs[i];
					callHistoricData(currentPair, count, cbAtivo);
				}
			}

			function getParameter() {
				percentageMin = $('#selPercentageMin').val();
				percentageMax = $('#selPercentageMax').val();
				candleTime = $('#selCandleTime').val();
				daysAnalyse = $('#selDays').val();
				martingales = $('#selMartingales').val();
				orderType = $('#selOrderType').val();
				timeInit = $('#selTimeInit').val();
				timeEnd = $('#selTimeEnd').val();
				cbAtivo = $('#cbAtivo').val();
			}

		function CalculateCountCandles() {
				var minutes = 15; // DEFAULT FOR M15
				switch (candleTime) {
					case 'M2':
						minutes = 2;
						break;
						case 'M2':
						minutes = 2;
						break;
					case 'M10':
						minutes = 10;
						break;
					case 'M15':
						minutes = 15;
						break;
					case 'M30':
						minutes = 30;
						break;
					case 'H1':
						minutes = 60;
						break;
					case 'H2':
						minutes = 120;
						break;
					case 'H4':
						minutes = 240;
						break;
				}


				var count = 60 / minutes;
				count = 24 * count;
				count = count * daysAnalyse;
				return count;
			}

			function callHistoricData(pair, count, cbAtivo) {
				var count_i = 0;
				if (cbAtivo == 0) {
					//var urlHist = "https://api-fxtrade.oanda.com/v1/candles?instrument="+pair+"&start=1565395200&end=1569283200&granularity=M1";
					//var urlHist = "https://api-fxtrade.oanda.com/v1/candles?instrument="+pair+"&start="+startDate+"&end="+endDate+"&granularity="+candleTime+"&candleFormat=midpoint";
					//var urlHist = "https://api-fxpractice.oanda.com/v3/instruments/"+pair+"/candles?from="+startDate+"&to="+endDate+"&granularity="+candleTime+"";
					var urlHist =
						'https://api-fxpractice.oanda.com/v3/instruments/' +
						pair +

						'/candles?granularity=' +
						candleTime +
						'&count=' +
						count;
					$.ajax({
						url: urlHist,
						headers: {
							Authorization: 'Bearer eb2326208921b413a87728832f191f03-d9be68b74884f7d3107b9f05ca305319',
						},
						type: 'GET',
						success: function (result) {
							CalculateHistoric(result);
						},
						error: function (error) {
							ErrorHistoric(error);
						},
					});
				} else {
					if (count_i == 0) {
						//(cbAtivo == pair && count_i == 0 ){
						//alert(cbAtivo);
						//count_i ++;
						var urlHist =
							'https://api-fxpractice.oanda.com/v3/instruments/' +
							pair +
							'/candles?granularity=' +
							candleTime +
							'&count=' +
							count;
						$.ajax({
							url: urlHist,
							headers: {
								Authorization:
									'Bearer  eb2326208921b413a87728832f191f03-d9be68b74884f7d3107b9f05ca305319',
							},
							type: 'GET',
							success: function (result) {
								CalculateHistoric(result);
							},
							error: function (error) {
								ErrorHistoric(error);
							},
						});
					}
				}
			}
			function CalculateHistoric(result) {
				var candles = result.candles;
				var candlesResult = [];
				for (var i = 0; i < candles.length; i++) {
					var candle = candles[i];

					var item = new Object();
					item.resultValue = candle.mid.o - candle.mid.c;
					item.date = ConvertDate(candle.time);
					item.result = GetStringResult(item.resultValue);
					item.percentDif = (item.resultValue * 100) / candle.mid.o;
					if (item.result === orderType) {
						item.win = true;
					} else {
						item.win = false;
					}

					//if(CheckTime(item.date)){

					var arrayTime = item.date.time.split(':');

					if (parseInt(arrayTime[0]) < parseInt(timeInit) || parseInt(arrayTime[0]) > parseInt(timeEnd)) {
						continue;
					}
					candlesResult.push(item);
				}
				var martinGaleResult = candlesResult;
				if (martingales > 0) {
					martinGaleResult = [];
					for (var i = 0; i < candlesResult.length; i++) {
						var candle = candlesResult[i];
						candle.nextCandles = GetNextMartingales(candlesResult, i);
						candle.win = candle.win === false ? GetMartingaleResult(candle) : true;
						martinGaleResult.push(candle);
					}
				}

				var timeGroupedCandles = Array.from(new Set(martinGaleResult.map((s) => s.date.time))).map((time) => {
					return {
						time: time,
						candles: martinGaleResult.filter((s) => s.date.time === time),
						pair: result.instrument,
					};
				});

				for (var i = 0; i < timeGroupedCandles.length; i++) {
					var currentGroup = timeGroupedCandles[i];

					currentGroup.winrate = 0;
					currentGroup.averageTickDif = 0;
					for (var z = 0; z < currentGroup.candles.length; z++) {
						var candle = currentGroup.candles[z];

						if (candle.win == true) {
							currentGroup.winrate++;
							currentGroup.averageTickDif += item.percentDif;
						}
					}
					currentGroup.averageTickDif = currentGroup.averageTickDif / currentGroup.winrate;

					currentGroup.winrate = (currentGroup.winrate * 100) / currentGroup.candles.length;

					if (currentGroup.winrate >= percentageMin && currentGroup.winrate <= percentageMax) {
						listBestPairTimes.push(currentGroup);
						continue;
					}
				}
				requestNumber--;
				if (requestNumber == 0) {
					DownloadTxt();
				}
			}

			function CheckTime(date) {
				var minDate = new Date();
				return true;
			}

			function GetMartingaleResult(candle) {
				var anyWin = candle.nextCandles.find((s) => s.win === true);

				return anyWin != undefined && anyWin != null > 0 ? true : false;
			}

			function GetNextMartingales(listCandles, index) {
				var nextCandles = [];
				var candle = listCandles[index];
				if (martingales > 0 && parseInt(index) + parseInt(martingales) < listCandles.length) {
					for (var i = 1; i <= martingales; i++) {
						var nextCandle = listCandles[index + i];
						nextCandles.push(nextCandle);
					}
					return nextCandles;
				} else {
					return nextCandles;
				}
			}

			function DownloadTxt(){
	 if(listBestPairTimes.length <= 0){
		alert('No signal found for the selected winrate and wales range.');
	 }
	listBestPairTimes.sort((a, b) => (a.time > b.time) ? 1 : -1)
	var listNumber = listBestPairTimes.length / 80;
	var i = 0
	var stringList2 = "LIST OF Panther Binary Trader BINARY SIGNALS _"+candleTime;
	for(var x = 0; x < listNumber; x++){
		var index = 1;
		var stringList = "This is Total Sh*t _"+candleTime;
		stringList2 +=  "\r\n- - - JOIN @futuresignala - - ";

		for(; i < listBestPairTimes.length; i++){
			var candle = listBestPairTimes[i];
			var arrayTime = candle.time.split(':');
			//alert(candle.pair);

			for(var z = 0; z < arrayTime.length; z++){
				 if(arrayTime[z] === "0"){
					arrayTime[z] = "00";
				 }
			}

/*             stringList += "\r\nE" + index + "=---------Entrada_" + index + "---------"
            stringList += "\r\nHora_" + index + "=" + arrayTime[0];
            stringList += "\r\nMinuto_" + index + "=" + arrayTime[1];
            stringList += "\r\nTipo_" + index + "=" + orderType;
            stringList += "\r\nPAR_" + index + "=" + candle.pair.replace('_', '');
            stringList += "\r\nvalor_" + index + "=1.0";
            stringList += "\r\nExpiracao_" + index + "=" + candleTime.substring(1, candleTime.length);
            stringList += "\r\nPermitir_Entrada_" + index + "=true"; */


            stringList2 += "\r\n "+candle.time+ ";"+candle.pair.replace('_', '')+ ";"+orderType+ ";"+candleTime.substring(1,candleTime.length);
			
            //stringList2 += "\r\n" + Math.abs(candle.averageTickDif.toFixed(5));
            //stringList2 += "\r\n- - - - - - - - - - - - - - - - - - - - - ";
			
			index++;

			if(i > 0 && (i+1) % 80 == 0){
			    i++;
				break;
			}

		}

/* 		stringList += "\r\ns_title_settings====== TRADING SETTINGS ============";
		stringList += "\r\nMartingaleType=0";
		stringList += "\r\nMartingaleSteps="+martingales;
		stringList += "\r\nMartingaleCoef=2.2"; */

		//download(percentageMin +" - " +percentageMax + '_' + orderType + '_' + candleTime + "ListaSinais_" +parseInt(x+1).toString() + ".set", stringList);


	}
	download(percentageMin +" - "+percentageMax + '_' + orderType + '_' + candleTime + 'PantherSignal.txt', stringList2);
				
			}

			function download(filename, text) {
				$('body').css('cursor', 'default');
				var element = document.createElement('a');
				element.setAttribute('href', 'data:text/plain;charset=utf-8,' + encodeURIComponent(text));
				element.setAttribute('download', filename);

				element.style.display = 'none';
				document.body.appendChild(element);

				element.click();

				document.body.removeChild(element);
			}

			function GetStringResult(value) {
				if (value > 0) {
					return 'PUT';
				} else if (value < 0) {
					return 'CALL';
				} else {
					return 'DRAW';
				}
			}

			function ErrorHistoric(error) {
				alert('Error');
			}

			function ConvertDate(time) {
				//var stringDate = unixTimestamp.toString().slice(0, -6);
				//unixTimestamp = parseInt(stringDate);
				var dateObj = new Date(time);
				var timeObj = new Object();
				timeObj.date = dateObj;

				timeObj.time = dateObj.getHours() + ':' + dateObj.getMinutes() ;

				return timeObj;
			}

			$('#formHist').submit(function (e) {
				e.preventDefault();
				return false;
			});
		</script>
	</body>
</html>
