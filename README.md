# git-pages

<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>김규영 이력서</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.8;
      background: #f4f6f8;
      padding: 2em;
      max-width: 900px;
      margin: auto;
      color: #2c3e50;
    }
    h1 {
      font-size: 2.4em;
      border-bottom: 2px solid #2980b9;
      padding-bottom: 0.3em;
      margin-bottom: 1em;
    }
    h2 {
      font-size: 1.8em;
      border-left: 5px solid #2980b9;
      padding-left: 10px;
      margin-top: 2em;
    }
    h3 {
      font-size: 1.4em;
      color: #34495e;
      margin-top: 1.2em;
    }
    a {
      color: #3498db;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    section {
      margin-bottom: 2em;
    }
    ul {
      list-style-type: disc;
      padding-left: 1.5em;
    }
    img {
      max-width: 150px;
      border-radius: 10px;
      margin-bottom: 1em;
    }
    .profile img {
      float: right;
      margin-left: 2em;
    }
  </style>
</head>
<body>
  <h1>김규영</h1>
  <section class="profile">
    <h2>프로필</h2>
    <p><img src="캡처.PNG" alt="프로필 이미지"/></p>
    <p>생년월일: 2000.01.16 (만 25세)</p>
    <p>전화번호: 010-7182-1508</p>
    <p>이메일: <a href="mailto:kyuyoungk@naver.com">kyuyoungk@naver.com</a></p>
    <p>GitHub: <a href="https://github.com/K-KY" target="_blank">https://github.com/K-KY</a></p>
  </section>

  <section>
    <h2>보유 기술</h2>
    <ul>
      <li><strong>언어:</strong> Java (상), Python (중), JavaScript (중), Dart (하)</li>
      <li><strong>도구:</strong> Docker (중), Jenkins (하), Nginx (하)</li>
      <li><strong>프레임워크:</strong> Spring Boot (상), FastAPI (중), Flutter (하)</li>
      <li><strong>클라우드 및 DB:</strong> MySQL (상), Oracle (하), MongoDB (하), GCP (중), AWS (하)</li>
    </ul>
  </section>

  <section>
    <h2>프로젝트</h2>
    <h3>DevLens</h3>
    <p>개발사 외주 프로젝트에서 협업 문제 해결을 위한 프로젝트 관리 플랫폼</p>
    <p><a href="https://github.com/seven-eleven-devlens/DevLens_BE" target="_blank">GitHub</a></p>
    <ul>
      <li>CI/CD 파이프라인 구축 (Jenkins)</li>
      <li>멀티모듈 배포 및 인프라 관리</li>
      <li>실시간 로그/성능 모니터링 서버 구축 (Loki, Grafana, Prometheus)</li>
    </ul>

    <h3>AI 파크</h3>
    <p>텍스트 음성 변환 및 음성 병합 플랫폼</p>
    <p><a href="https://github.com/team5re5/5RE5PARK_BACKEND" target="_blank">GitHub</a></p>
    <ul>
      <li>Java Sound API를 활용한 오디오 병합</li>
      <li>파일 포맷 검사 및 변경</li>
      <li>AWS Lambda 활용하여 OOM 문제 해결</li>
    </ul>

    <h3>BeeSpace</h3>
    <p>프로젝트 홍보 및 피드백 커뮤니티 플랫폼</p>
    <p><a href="https://github.com/CreaviSpace" target="_blank">GitHub</a></p>
    <ul>
      <li>JWT 기반 로그인, 재발급 구현</li>
      <li>SpringSecurity 기반 사용자 권한 설정</li>
      <li>JPA N+1 문제 해결</li>
    </ul>
  </section>
</body>
</html>
