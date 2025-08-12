<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <title>Webhook送信ページ</title>
</head>
<body>
  <h2>Webhook URLにメッセージ送信するよ</h2>
  <label>Webhook URL: <input type="text" id="webhookUrl" style="width: 400px;" placeholder="WebhookのURLを入れてね" /></label><br><br>
  <label>送信メッセージ: <input type="text" id="message" placeholder="送信したい言葉を入力" /></label><br><br>
  <button onclick="sendMessage()">送信する！</button>
  <p id="status"></p>

  <script>
    async function sendMessage() {
      const url = document.getElementById('webhookUrl').value.trim();
      const content = document.getElementById('message').value.trim();
      const status = document.getElementById('status');
      
      if (!url || !content) {
        status.textContent = 'Webhook URLとメッセージは両方入力してね！';
        status.style.color = 'red';
        return;
      }
      
      try {
        const res = await fetch(url, {
          method: 'POST',
          headers: {
            'Content-Type': 'application/json'
          },
          body: JSON.stringify({ content })
        });
        if (res.ok) {
          status.textContent = 'メッセージ送信したよ！✨';
          status.style.color = 'green';
        } else {
          status.textContent = `送信失敗…ステータスコード: ${res.status}`;
          status.style.color = 'red';
        }
      } catch (error) {
        status.textContent = 'エラー発生！Webhook URLを確認してください';
        status.style.color = 'red';
      }
    }
  </script>
</body>
</html>
