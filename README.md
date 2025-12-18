# sol729.github.io
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>iMac Style Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }

    body {
      background: linear-gradient(180deg, #f2f3f5, #e6e7eb);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    /* iMac 전체 프레임 */
    .imac {
      width: 900px;
    }

    /* 상단 화면 */
    .screen {
      background: #1c1c1e;
      border-radius: 18px 18px 10px 10px;
      padding: 14px;
      box-shadow: 0 30px 60px rgba(0,0,0,0.25);
    }

    /* 베젤 */
    .bezel {
