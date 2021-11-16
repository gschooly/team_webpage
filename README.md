<!DOCTYPE html>
<html>

<head>
  <title>2021_4M 5%팀 웹퍼이지</title>
  <style>
    @font-face {
      font-family: 'Hahmlet-Bold';
      src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2110@1.0/Hahmlet-Bold.woff2') format('woff2');
      font-weight: normal;
      font-style: normal;
    }

    @font-face {
      font-family: 'Hahmlet-ExtraLight';
      src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2110@1.0/Hahmlet-ExtraLight.woff2') format('woff2');
      font-weight: normal;
      font-style: normal;
    }

    table {
      width: 60%;
      height: 100px;
      margin: auto;
      text-align: center;
    }

    .b_title {
      font-family: 'Hahmlet-Bold';
      color: brown;
    }

    .s_title {
      font-family: 'Hahmlet-Bold';
      color: chocolate;
      font-size: 60px;
    }

    .contents {
      font-family: 'Hahmlet-ExtraLight';
      color: darkgoldenrod;
      font-size: 25px;

    }

    a {
      background-color: blanchedalmond;
    }
  </style>
</head>

<body>
  <div class="header">
    <a href="./home.html" class="Logo"><img src="./home_scr/logo.png" alt=""></a>
    <div class="header_tab hidden" align="right">
      <a href="./team_int.html">팀 소개</a>
      <a href="./project_int.html">프로젝트 소개</a>
      <a href="./member_int.html">팀원 소개</a>
    </div>
    <a href="#" class="toggleBtn">
      <i class="fas fa-bars" onclick="toggle()"></i>
    </a>
  </div>

  <section style="margin:10px">
    <center>
      <header>
        <h1 class="b_title">팀소개</h1>
      </header>
      <h2 class="s_title">당신의 문해력은 안녕하십니까</h3><br>
        <p class="contents">안녕하세요, 저희는 '청소년의 문해력이 부족하다'라는 주제를탐구하고 해결하기 위해 노력하고 있는 5%팀 입니다</p>
    </center>
  </section><br><br>

  <section style="margin:10px">
    <center>
      <header>
        <h1 class="b_title">프로젝트 소개</h1>
      </header>
      <article>
        <h3 id="project"><strong>"청소년의 문해력이 부족하다"</strong></p>
      </article><br>
      <h2 class="s_title">문해력이란?</h3>
        <p class="contents">글 사이에 숨겨진 의미를 비판적으로 읽을 수 있는 능력</p><br>
        <h2 class="s_title">프로젝트를 시작하게 된 이유</h3>
          <li class="contents">글을 읽지 못하는 아이들</li>
          <li class="contents">모르는 단어 때문에 진행되지 않는 수업</li><br>
          <p class="contents"><strong>청소년들은 낮아지는 문해력으로 인해 수동적이고<br> 스스로 생각하지 못하는 사람이 된다</strong></p><br>
          <h2 class="s_title">문해력 저하 현재 실태</h3>
            <table>
              <tr>
                <td><img alt="" src="./pisa.jpeg" width="300" /></td>
                <td><img alt="" src="./11.jpeg" width="300" /></td>
                <td><img alt="" src="./56.jpeg" width="300" /></td>
              </tr>
              <tr>
                <td class="contents">낮아지는 PISA(읽기 소양 성취 비율) 순위</td>
                <td class="contents">초등 수준의 문해력을 가진 11%의 중학생</td>
                <td class="contents">기업 191개의 MZ세대 국어 능력 평가 결과 '부족하다' 56%</td>
              </tr>
            </table><br><br>
            <h2 class="s_title">문제 발생 이유</h3>
              <ol type="i">
                <li class="contents">미디어 사용 증가로 인한 독서량 저하</li>
                <li class="contents">독서량 저하로 인해 사고하는 능력 상실</li>
                <li class="contents">보기에 편한 미디어로 회귀</li>
              </ol><br>
              <h2 class="s_title">진행 한 활동</h3>
                <h2 class="s_title">진행 할 활동</h3>
                  <li class="contents">설문조사</li>
                  <li class="contents">전문가 인터뷰</li>
                  <h2 class="s_title">최종목표</h3>
                    <p class="contents">청소년들이 문해력에 대해 이해하고 증진시키는 것</p>
    </center>
  </section><br><br>

<section style="margin:10px">
    <center>
      <h1 class="b_title">팀원 소개</h1>
      <span><img src="./포인.png" width="280" /></span>
      <span><img src="./오냐.png" width="280" /></span>
      <span><img src="./가온.png" width="280" /></span>
      <span><img src="./와이.png" width="280" /></span>
    </center>
  </section>
</body>

</html>