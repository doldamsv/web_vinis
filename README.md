# web_vinis
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>석포교회</title>
  <style>
    body {
      font-family: '맑은 고딕', Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
    }
    header {
      background-color: #448ccb;
      color: #fff;
      padding: 30px 0 10px 0;
      text-align: center;
    }
    nav {
      background: #316998;
      padding: 10px 0;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 20px;
      text-decoration: none;
      font-size: 1.1em;
      font-weight: bold;
    }
    .main-image {
      width: 100%;
      max-height: 320px;
      object-fit: cover;
      display: block;
      margin: 0 auto;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.04);
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      border-bottom: 2px solid #448ccb;
      padding-bottom: 6px;
      margin-bottom: 15px;
      color: #316998;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    th, td {
      border: 1px solid #bbb;
      padding: 10px 0;
      text-align: center;
    }
    .map {
      width: 100%;
      height: 300px;
      margin-top: 10px;
      border-radius: 8px;
      overflow: hidden;
    }
    footer {
      background: #316998;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>석포교회</h1>
    <p>하나님의 사랑이 넘치는 석포교회에 오신 여러분을 환영합니다.</p>
  </header>
  <nav>
    <a href="#">홈</a>
    <a href="#">소개</a>
    <a href="#">예배안내</a>
    <a href="#">오시는길</a>
    <a href="#">교회소식</a>
  </nav>

  <!-- 메인 이미지(교회 외부 이미지 URL로 교체 가능) -->
  <img class="main-image" src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1050&q=80" alt="교회 전경 이미지">

  <main>
    <section>
      <h2>교회 소개</h2>
      <p>
        석포교회는 예수 그리스도의 사랑과 복음을 전하는 신앙 공동체입니다.<br>
        진리와 사랑 위에 세워진 석포교회에서 늘 평안과 은혜가 넘치시길 기도합니다.
      </p>
    </section>

    <section>
      <h2>예배 안내</h2>
      <table>
        <tr>
          <th>예배 종류</th>
          <th>시간</th>
          <th>장소</th>
        </tr>
        <tr>
          <td>주일예배</td>
          <td>주일 오전 11시</td>
          <td>본당</td>
        </tr>
        <tr>
          <td>수요예배</td>
          <td>수요일 오후 7시 30분</td>
          <td>본당</td>
        </tr>
        <tr>
          <td>새벽기도회</td>
          <td>월~금 오전 5시</td>
          <td>본당</td>
        </tr>
      </table>
    </section>

    <section>
      <h2>오시는 길</h2>
      <div class="map">
        <!-- 네이버 지도 예시(실제 위치에 맞게 수정 필요) -->
        <iframe src="https://map.naver.com/p/search/%EB%B6%80%EC%82%B0%20%EB%82%A8%EA%B5%AC%20%EB%8C%80%EC%97%B0%EB%8F%99%20%EC%84%9D%ED%8F%AC%EA%B5%90%ED%9A%8C" width="100%" height="300" frameborder="0" style="border:0" allowfullscreen></iframe>
      </div>
      <p>주소: 부산광역시 남구 대연동 123-45 (예시 주소, 실제 주소로 수정 가능)</p>
      <p>전화: 051-XXX-XXXX</p>
    </section>
  </main>

  <footer>
    © 2025 석포교회. All Rights Reserved.
  </footer>
</body>
</html>
