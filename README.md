<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
	<style>
		body{font-family:'SCore Dream', sans-serif; text-align: center;}
		
	</style>
</head>
<body>
<h1>< 발음하기 어려운 영어 단어 ></h1>
<p>단어를 클릭하면 발음이 나옵니다!</p>

<img id = "word1" src = "word1.png" width="500" height= "50" onmouseover="this.style.filter='invert(100%)';" 
onmouseout = "this.style.filter = 'none';">
<img id = "word2" src = "word2.png" width="500" height= "50"
onmouseover="this.style.filter='invert(100%)';" 
onmouseout = "this.style.filter = 'none';">
<img id = "word3" src = "word3.png" width="500" height= "50"
onmouseover="this.style.filter='invert(100%)';" 
onmouseout = "this.style.filter = 'none';">
<img id = "word4" src = "word4.png" width="500" height= "50"
onmouseover="this.style.filter='invert(100%)';" 
onmouseout = "this.style.filter = 'none';">

<h2>단어 뜻풀이</h2>

<p> 1. Floccinaucinihilipilification: 무가치한 것을 경시하는 행동 </p>
<p> 2. Pneumonoultramicroscopicsilicovolcanoconiosis: 폐에서 발생하는 질병인 진폐증을 뜻함 </p>
<p> 3. Worcestershire: '우스터셔', 잉글랜드 남서부의 옛 주 </p>
<p> 4. antidisestablishmentarianism: 국교 폐지 조례 반대론: 국교에 대하여 국가가 지지와 시인을 철폐하는 데 대한 반대</p>


<audio id = "word1pro" src = "word1pro.mp3"></audio>
<audio id = "word2pro" src = "word2pro.mp3"></audio>
<audio id = "word3pro" src = "word3pro.mp3"></audio>
<audio id = "word4pro" src = "word4pro.mp3"></audio>

<script>
	
word1.onclick = function(){
	word1pro.play();
}

word2.onclick = function(){
	word2pro.play();
}

word3.onclick = function(){
	word3pro.play();
}

word4.onclick = function(){
	word4pro.play();
}


</script>


</body>
</html>
