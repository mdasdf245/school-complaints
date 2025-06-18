<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>학교 민원처리기</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1> 진부고등학교 민원처리기</h1>
        <p>불편사항이나 건의사항을 입력해주세요!</p>
    </header>

    <main>
        <form action="https://formsubmit.co/kmj449489@gmail.com" method="POST">
            <label for="name">이름:</label>
            <input type="text" id="name" name="name" required>

            <label for="grade">학년/반:</label>
            <input type="text" id="grade" name="grade" required>

            <label for="category">민원 유형:</label>
            <select id="category" name="category">
                <option value="시설 불편">시설 불편</option>
                <option value="급식 문제">급식 문제</option>
                <option value="수업 관련">수업 관련</option>
                <option value="기타">기타</option>
            </select>

            <label for="message">내용:</label>
            <textarea id="message" name="message" rows="6" required></textarea>

            <button type="submit">민원 접수하기</button>
        </form>
    </main>

    <footer>
        <p>&copy; 2025 학교 민원처리 시스템</p>
    </footer>
</body>
</html>

