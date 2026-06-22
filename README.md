# AntangStory
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>안수민 Portfolio</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f6f8;
            color: #222;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #1f2937, #374151);
            color: white;
            padding: 80px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 44px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 20px;
            margin: 0;
        }

        section {
            max-width: 1000px;
            margin: 0 auto;
            padding: 50px 20px;
        }

        h2 {
            font-size: 30px;
            border-left: 6px solid #1f2937;
            padding-left: 12px;
            margin-bottom: 25px;
        }

        h3 {
            margin-top: 25px;
            color: #1f2937;
        }

        .card {
            background-color: white;
            padding: 30px;
            border-radius: 14px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
            margin-bottom: 25px;
        }

        .project-title {
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 10px;
            color: #111827;
        }

        .project-info {
            color: #555;
            margin-bottom: 20px;
        }

        .tag {
            display: inline-block;
            background-color: #1f2937;
            color: white;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 14px;
            margin: 4px;
        }

        ul {
            padding-left: 22px;
        }

        li {
            margin-bottom: 8px;
        }

        footer {
            background-color: #1f2937;
            color: white;
            text-align: center;
            padding: 30px 20px;
            margin-top: 40px;
        }

        a {
            color: #2563eb;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        .highlight {
            font-weight: bold;
            color: #111827;
        }
    </style>
</head>
<body>

    <header>
        <h1>안수민 Portfolio</h1>
        <p>Unity와 C#을 중심으로 게임 프로그래밍 역량을 쌓고 있는 개발자 지망생입니다.</p>
    </header>

    <section>
        <h2>About Me</h2>
        <div class="card">
            <p>
                안녕하세요. 저는 게임 개발 직군을 목표로 Unity와 C#을 중심으로
                게임 프로그래밍 역량을 쌓고 있는 안수민입니다.
            </p>
            <p>
                게임 오브젝트의 이동, 충돌, 공격 처리, UI 연동, 게임 진행 흐름 등
                실제 플레이에 필요한 기능을 직접 구현하며 개발 경험을 쌓아왔습니다.
            </p>
            <p>
                단순히 화면에 보이는 결과만 만드는 것이 아니라,
                코드 구조와 유지보수성, 기능 확장 가능성을 고려하는 개발자가 되는 것을 목표로 하고 있습니다.
            </p>
        </div>
    </section>

    <section>
        <h2>Portfolio</h2>

        <div class="card">
            <div class="project-title">진주도둑들</div>
            <p class="project-info">
                2D 게임 프로젝트 / STOVE Indie 출시 경험 / 팀 프로젝트
            </p>

            <p>
                <strong>진주도둑들</strong>은 스토브인디에 출시했던 2D 게임 프로젝트입니다.
                팀 프로젝트로 진행되었으며, 실제 출시 경험을 통해 게임 개발 과정과
                배포 과정의 흐름을 경험할 수 있었습니다.
            </p>

            <p>
                이 프로젝트에서 Unity와 C#을 활용하여 게임 플레이에 필요한 기능 구현과
                시스템 제작을 경험했습니다. 캐릭터 동작, 오브젝트 상호작용,
                UI 구성, 게임 진행 흐름 등 실제 게임 플레이와 연결되는 프로그래밍 요소를 다뤘습니다.
            </p>

            <h3>프로그래밍 경험</h3>
            <ul>
                <li>Unity 기반 2D 게임 기능 구현</li>
                <li>C# 스크립트를 활용한 게임 로직 작성</li>
                <li>캐릭터 이동 및 오브젝트 상호작용 처리</li>
                <li>충돌 판정과 게임 진행 흐름 구현</li>
                <li>UI 기능 연동 및 게임 상태 관리</li>
                <li>팀 프로젝트 기반 개발 및 출시 경험</li>
            </ul>

            <h3>사용 기술</h3>
            <div>
                <span class="tag">Unity</span>
                <span class="tag">C#</span>
                <span class="tag">Game Programming</span>
                <span class="tag">2D Game</span>
                <span class="tag">STOVE Indie</span>
                <span class="tag">Team Project</span>
            </div>
        </div>
    </section>

    <section>
        <h2>Skills</h2>
        <div class="card">
            <ul>
                <li><span class="highlight">Language:</span> C#, C</li>
                <li><span class="highlight">Game Engine:</span> Unity</li>
                <li><span class="highlight">Version Control:</span> GitHub</li>
                <li><span class="highlight">Programming:</span> 게임 로직 구현, 충돌 처리, UI 연동, 상태 관리</li>
                <li><span class="highlight">Interest:</span> 게임 시스템 구조, 전투 시스템, 오브젝트 관리, 코드 설계</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>Contact</h2>
        <div class="card">
            <p>
                GitHub 또는 이메일을 통해 연락할 수 있습니다.
            </p>
            <p>
                GitHub: <a href="#">GitHub 링크를 여기에 넣으세요</a>
            </p>
            <p>
                Email: <a href="mailto:bamtollry@gmail.com">bamtollry@gmail.com</a>
            </p>
        </div>
    </section>

    <footer>
        <p>© 2026 안수민 Portfolio. All rights reserved.</p>
    </footer>

</body>
</html>
