# 텍스트를 덩어리로 묶어 주는 태그

> text-1.html

```html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8" />
    <title>제주 이색 여행지</title>
  </head>
  <body>
    <h1>제주 이색 여행지</h1>
    <h2>야외 텐트를 닮은 건축물 "테쉬폰"</h2>
    <p>
      아일랜드 출신 임피제 신부가 1954년 제주에 오면서 목장 숙소로 짓기 시작한
      후 사료공장, 성당으로 활용됐습니다.
    </p>
    <p>
      제주에서 점차 다른 지방으로 보급됐지만 현재 제주에만 건축물이 남아있는데,
      <br />
      국내 근현대 건축사의 한 페이지를 보여주는 가치를 지닌다고 전문가들은
      평가합니다.
    </p>
    <hr />
    <blockquote>
      성이시돌목장은 제주특별자치도 제주시 한림읍 금악리에 있는 목장이다. 특히
      이시돌목장은 제주 지역 최초의 전기업목장(全企業牧場)으로 1961년 11월 말
      제주시 한림읍 금악리에 세워 양돈 사업을 실시하였으며 면양을 사육하였던
      것으로 알려져 있다. 이시돌목장의 특색있는 건축양식으로 테쉬폰도 유명하다.
      (출처:향토문화전자대전)
    </blockquote>
  </body>
</html>
```

> text-2.html

```html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="utf-8" />
    <title>로컬 스토리지(Local Storage)를 저장하는 함수</title>
  </head>
  <body>
    <h3>로컬 스토리지(Local Storage)를 저장하는 함수 :</h3>
    <pre>
     function savetheLocal(){
          var second = document.getElementById("second");
          var thevalue = second.value;
          localStorage.setItem(1, thevalue);
          gettheLocal();
     }    
	</pre
    >
  </body>
</html>
```