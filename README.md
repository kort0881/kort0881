<!-- ============================================================ -->
<!--  БЛОК ДОНАТОВ С МИГАЮЩИМИ КНОПКАМИ, QR-КОДАМИ И СПИСКОМ СЕТЕЙ -->
<!-- ============================================================ -->

<div align="center" id="donate">

  <h2>💰 Поддержать проект</h2>

  <!-- МИГАЮЩАЯ КНОПКА "ПОДДЕРЖАТЬ" (ссылка на раздел с крипто-адресами) -->
  <a href="#crypto" 
     style="display: inline-block; 
            padding: 16px 40px; 
            background: linear-gradient(45deg, #f7971e, #ffd200); 
            color: #1a1a1a; 
            font-size: 26px; 
            font-weight: 800; 
            border-radius: 50px; 
            text-decoration: none; 
            box-shadow: 0 8px 25px rgba(255, 215, 0, 0.6); 
            animation: pulse-blink 1.4s infinite ease-in-out;
            letter-spacing: 1px;
            border: 2px solid #fff;">
    ⚡ ПОДДЕРЖАТЬ
  </a>

  <br><br>

  <!-- МИГАЮЩАЯ КНОПКА "SPONSOR ON GITHUB" (бейдж с анимацией) -->
  <a href="https://github.com/sponsors/kort0881" 
     style="display: inline-block; 
            animation: pulse-blink 1.8s infinite ease-in-out;
            border-radius: 10px;
            overflow: hidden;">
    <img src="https://img.shields.io/badge/Sponsor%20💚-kort0881-brightgreen.svg?logo=github&logoColor=white&style=for-the-badge" 
         alt="Sponsor kort0881" 
         style="display: block;">
  </a>

  <br><br>

  <!-- ============ СПИСОК СЕТЕЙ И QR-КОДЫ ============ -->
  <div id="crypto">
    <table align="center" border="0" cellpadding="15" cellspacing="0" style="border-collapse: collapse; background: #f8f9fa; border-radius: 20px; box-shadow: 0 4px 20px rgba(0,0,0,0.08);">
      <tr>
        <td align="center" valign="middle" style="padding: 20px 30px;">
          <strong style="font-size: 20px; color: #2a9d8f;">🟢 USDT (TRC-20)</strong><br>
          <code style="background: #e9ecef; padding: 6px 12px; border-radius: 8px; font-size: 14px;">TDpXaQ51rCyHcwTtf8pFoZVumBTHc5zUEv</code><br><br>
          <img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=TDpXaQ51rCyHcwTtf8pFoZVumBTHc5zUEv" 
               alt="USDT TRC-20 QR" 
               width="160" height="160" 
               style="border-radius: 12px; border: 2px solid #2a9d8f;">
        </td>
        <td align="center" valign="middle" style="padding: 20px 30px;">
          <strong style="font-size: 20px; color: #6d28d9;">🟣 SOL (Solana)</strong><br>
          <code style="background: #e9ecef; padding: 6px 12px; border-radius: 8px; font-size: 14px;">UQBulszePXnd4_jPFOZT3tErjWhkgKNjaPT2_1lYP_SqY0ge</code><br><br>
          <img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=UQBulszePXnd4_jPFOZT3tErjWhkgKNjaPT2_1lYP_SqY0ge" 
               alt="SOL QR" 
               width="160" height="160" 
               style="border-radius: 12px; border: 2px solid #6d28d9;">
        </td>
      </tr>
    </table>
  </div>

  <br>

  <!-- ПРЕДУПРЕЖДЕНИЕ -->
  <div style="background: #fff3cd; padding: 12px 20px; border-radius: 12px; display: inline-block; border-left: 6px solid #ffc107;">
    ⚠️ <strong>Важно:</strong> Отправляйте USDT <strong>ТОЛЬКО</strong> в сети TRC-20 (Tron)!<br>
    Отправка в другую сеть = <strong style="color: #d9534f;">потеря средств</strong> 🔥
  </div>

  <!-- ============ СТИЛИ ДЛЯ АНИМАЦИИ ============ -->
  <style>
    @keyframes pulse-blink {
      0%   { transform: scale(1); opacity: 1; filter: drop-shadow(0 0 5px rgba(255,215,0,0.3)); }
      50%  { transform: scale(1.06); opacity: 0.85; filter: drop-shadow(0 0 20px rgba(255,215,0,0.9)); }
      100% { transform: scale(1); opacity: 1; filter: drop-shadow(0 0 5px rgba(255,215,0,0.3)); }
    }
  </style>

</div>
<!-- ============================================================ -->
<!--  КОНЕЦ БЛОКА ДОНАТОВ                                          -->
<!-- ============================================================ -->
