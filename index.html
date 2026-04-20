<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>日本水之國-滋賀十日行</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #005A9C; /* 琵琶湖深藍 */
            --secondary: #4BA3E3; /* 水之國淺藍 */
            --accent: #FF7F50; /* 亮點橘色 */
            --bg: #F4F7F6;
            --text: #333;
            --card-bg: #FFFFFF;
        }
        * { box-sizing: border-box; }
        body {
            font-family: 'PingFang TC', 'Microsoft JhengHei', sans-serif;
            margin: 0; padding: 0;
            background-color: var(--bg);
            color: var(--text);
            display: flex; flex-direction: column; height: 100vh;
        }
        /* 頂部導覽 */
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white; padding: 20px 15px;
            text-align: center; box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            position: sticky; top: 0; z-index: 100;
        }
        header h1 { margin: 0; font-size: 1.4rem; letter-spacing: 1px; }
        header p { margin: 5px 0 0; font-size: 0.85rem; opacity: 0.9; }
        
        /* 底部/側邊導覽列 */
        .nav-bar {
            display: flex; background: white; box-shadow: 0 -2px 10px rgba(0,0,0,0.05);
            order: 3; /* 手機版預設在底部 */
        }
        .nav-bar button {
            flex: 1; padding: 12px 0; border: none; background: none;
            color: #888; font-size: 0.8rem; cursor: pointer;
            display: flex; flex-direction: column; align-items: center; gap: 4px;
            transition: all 0.3s;
        }
        .nav-bar button i { font-size: 1.2rem; }
        .nav-bar button.active { color: var(--primary); border-top: 3px solid var(--primary); font-weight: bold; }
        
        /* 內容區塊 */
        .content { flex: 1; overflow-y: auto; padding: 15px; padding-bottom: 30px; order: 2; }
        .tab-section { display: none; animation: fadeIn 0.4s ease; }
        .tab-section.active { display: block; }
        
        /* 卡片設計 */
        .card {
            background: var(--card-bg); border-radius: 12px; padding: 15px;
            margin-bottom: 15px; box-shadow: 0 2px 8px rgba(0,0,0,0.06);
            border-left: 5px solid var(--secondary);
        }
        .card h3 { margin: 0 0 10px 0; color: var(--primary); font-size: 1.1rem; display: flex; align-items: center; gap: 8px;}
        .card-row { display: flex; justify-content: space-between; margin-bottom: 8px; font-size: 0.9rem;}
        .badge { background: #e0f0ff; color: var(--primary); padding: 3px 8px; border-radius: 20px; font-size: 0.8rem; font-weight:bold;}
        .badge.warn { background: #ffe8e0; color: #d35400; }
        
        /* 時間軸設計 (用於每日行程) */
        .timeline { position: relative; padding-left: 20px; margin-top: 15px; }
        .timeline::before {
            content: ''; position: absolute; left: 0; top: 0; bottom: 0;
            width: 2px; background: #ddd;
        }
        .time-item { position: relative; margin-bottom: 20px; }
        .time-item::before {
            content: ''; position: absolute; left: -25px; top: 3px;
            width: 12px; height: 12px; border-radius: 50%;
            background: var(--accent); border: 2px solid white; box-shadow: 0 0 0 2px var(--accent);
        }
        .time-header { font-weight: bold; color: var(--primary); margin-bottom: 5px; display:flex; align-items: center; gap:10px;}
        .time-desc { font-size: 0.95rem; line-height: 1.5; color: #555; background: white; padding: 10px; border-radius: 8px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); border: 1px solid #eee;}
        .price-tag { color: #d35400; font-weight: bold; font-size: 0.85rem;}
        
        /* 標籤切換 (行程天數) */
        .day-tabs { display: flex; overflow-x: auto; gap: 10px; padding-bottom: 10px; margin-bottom: 15px; }
        .day-tabs::-webkit-scrollbar { height: 4px; }
        .day-tabs::-webkit-scrollbar-thumb { background: #ccc; border-radius: 4px; }
        .day-btn {
            background: white; border: 1px solid #ddd; padding: 8px 15px;
            border-radius: 20px; white-space: nowrap; cursor: pointer; color: #555;
        }
        .day-btn.active { background: var(--primary); color: white; border-color: var(--primary); }
        .day-content { display: none; }
        .day-content.active { display: block; animation: fadeIn 0.3s; }

        @keyframes fadeIn { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }

        /* 電腦版微調 */
        @media (min-width: 768px) {
            body { flex-direction: row; flex-wrap: wrap; }
            header { width: 100%; order: 1; }
            .nav-bar { width: 100px; flex-direction: column; order: 2; height: calc(100vh - 60px); }
            .nav-bar button { padding: 20px 0; border-top: none; border-left: 3px solid transparent; }
            .nav-bar button.active { border-top: none; border-left: 3px solid var(--primary); }
            .content { width: calc(100% - 100px); order: 3; padding: 30px; }
        }
    </style>
</head>
<body>

    <header>
        <h1>💧 日本水之國-滋賀十日行</h1>
        <p>2025.05.07 - 2025.05.16 ｜ 旅人筆記</p>
    </header>

    <nav class="nav-bar">
        <button class="active" onclick="switchSection('itinerary')"><i class="fa-solid fa-map-location-dot"></i>行程</button>
        <button onclick="switchSection('flight')"><i class="fa-solid fa-plane-departure"></i>航班/交通</button>
        <button onclick="switchSection('hotel')"><i class="fa-solid fa-bed"></i>住宿</button>
        <button onclick="switchSection('info')"><i class="fa-solid fa-circle-exclamation"></i>重要須知</button>
    </nav>

    <main class="content">
        
        <section id="itinerary" class="tab-section active">
            <div class="day-tabs">
                <button class="day-btn active" onclick="switchDay('d1')">D1 大阪</button>
                <button class="day-btn" onclick="switchDay('d2')">D2 萬博</button>
                <button class="day-btn" onclick="switchDay('d3')">D3 京都</button>
                <button class="day-btn" onclick="switchDay('d6')">D6 滋賀</button>
                <button class="day-btn" onclick="switchDay('d8')">D8 近江</button>
            </div>

            <div id="d1" class="day-content active">
                <div class="card">
                    <h3><i class="fa-solid fa-sun"></i> 5/07 (Wed) - 難波商圈與京瓷巨蛋</h3>
                    <p style="font-size: 0.85rem; color:#666;">氣溫: 14-22度 | 降雨機率: 10%</p>
                    <div class="timeline">
                        <div class="time-item">
                            <div class="time-header">10:30 - 12:10 <span class="badge">交通</span></div>
                            <div class="time-desc">
                                抵達關西空港(KIX)。11:26 搭乘 <b>南海電鐵空港急行</b> 前往難波。<br>
                                <span class="price-tag"><i class="fa-solid fa-coins"></i> 930円 (約45分)</span>
                            </div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">12:30 - 14:00 <span class="badge warn">美食預約</span></div>
                            <div class="time-desc">
                                難波駅 E3 會合寄放行李。<br>
                                🍽️ <b>蟹道樂 道頓堀本店</b> (已預約 12:30)<br>
                                <span class="price-tag"><i class="fa-solid fa-coins"></i> 預估 7,000円</span>
                            </div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">14:10 - 16:00 <span class="badge">景點</span></div>
                            <div class="time-desc">逛日本橋商圈 (動漫聖地)、黑門市場。可去買 <b>玉製家和菓子</b> (900円)。</div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">16:40 - 17:00 <span class="badge">住宿</span></div>
                            <div class="time-desc">搭乘御堂筋線至梅田 (240円)。前往 <b>阪急龍仕柏飯店</b> 9樓大廳 Check-in。</div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">17:30 - 21:00 <span class="badge warn">重點行程</span></div>
                            <div class="time-desc">
                                搭乘長堀鶴見綠地線至 <b>大阪京瓷巨蛋</b>。<br>
                                ⚾ 歐力士猛牛 V.S. 日本火腿 (18:00開賽)。上段C指定席 三壘側。<br>
                                <span class="price-tag"><i class="fa-solid fa-coins"></i> 門票 2,700円</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div id="d2" class="day-content">
                <div class="card">
                    <h3><i class="fa-solid fa-earth-americas"></i> 5/08 (Thu) - 萬博紀念公園 & EXPO 2025</h3>
                    <div class="timeline">
                        <div class="time-item">
                            <div class="time-header">08:34 - 09:30 <span class="badge">交通</span></div>
                            <div class="time-desc">搭乘阪急京都線轉單軌電車前往萬博紀念公園。</div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">10:00 - 11:20 <span class="badge warn">預約景點</span></div>
                            <div class="time-desc">
                                參觀 <b>太陽之塔</b> (已預約10:00入場，980円)，接著參觀 EXPO'70 展示館 (500円)。
                            </div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">15:00 - 22:00 <span class="badge warn">EXPO 2025</span></div>
                            <div class="time-desc">
                                抵達夢洲會場 (全面電子支付！)。<br>
                                參觀 <b>PASONA</b> 與 <b>TECH WORLD (台灣館)</b> (皆已預約)。<br>
                                19:30 觀賞水舞表演。結束後可至 <b>咲洲宇宙塔展望台</b> 看夜景 (1,200円)。
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div id="d6" class="day-content">
                <div class="card">
                    <h3><i class="fa-solid fa-car"></i> 5/12 (Mon) - 琵琶湖自駕遊</h3>
                    <div class="timeline">
                        <div class="time-item">
                            <div class="time-header">08:00 <span class="badge warn">租車</span></div>
                            <div class="time-desc"><b>ORIX 大津駅南口店</b> 取車。預約番號: W7201882。費用: 24,915円 (到店付款)。</div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">09:00 - 14:00 <span class="badge">景點</span></div>
                            <div class="time-desc">
                                ⛩️ <b>近江神宮</b> (百人一首聖地)<br>
                                ⛩️ <b>浮御堂</b> (近江八景)<br>
                                ⛩️ <b>白鬚神社</b> (湖上鳥居絕景，午餐於 Seikousha Cafe)
                            </div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">18:30 - 20:30 <span class="badge warn">美食預約</span></div>
                            <div class="time-desc">
                                🍽️ <b>鮎茶屋かわせ</b> (已預約 18:30，兩小時用餐)。<br>
                                結束後前往美爵溫泉酒店 Check-in。
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div id="d8" class="day-content">
                <div class="card">
                    <h3><i class="fa-solid fa-water"></i> 5/14 (Wed) - 近江八幡水鄉之美</h3>
                    <div class="timeline">
                        <div class="time-item">
                            <div class="time-header">08:10 - 10:50 <span class="badge">歷史</span></div>
                            <div class="time-desc">參觀 <b>安土城跡</b> (700円) 與 <b>天主信長之館</b>。</div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">11:10 - 12:50 <span class="badge">甜點</span></div>
                            <div class="time-desc">🍰 <b>La Collina</b> 享用知名現烤年輪蛋糕 (預估1,500円)。</div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">14:10 - 15:00 <span class="badge warn">遊船</span></div>
                            <div class="time-desc">🚣 <b>八幡堀遊船</b> (14:20 觀光船出發，單趟約35分鐘，1,500円)。</div>
                        </div>
                        <div class="time-item">
                            <div class="time-header">19:00 - 21:30 <span class="badge warn">大餐預約</span></div>
                            <div class="time-desc">
                                19:00 於 ORIX 大津還車 (記得加滿油留收據！)。<br>
                                🥩 <b>松喜屋</b> (已預約 19:30，頂級近江牛，預估 11,000円)。
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <p style="text-align: center; color: #888; font-size: 0.85rem; margin-top: 20px;">*其他天數可由原始碼依此格式補齊</p>
        </section>

        <section id="flight" class="tab-section">
            <div class="card">
                <h3><i class="fa-solid fa-plane"></i> 台灣虎航 Tigerair (訂位代號: SCBS9K)</h3>
                <div class="card-row">
                    <span><b>去程 (5/07 Wed)</b></span>
                    <span class="badge">IT210</span>
                </div>
                <p style="margin:0 0 10px 0; font-size:0.9rem;">06:40 桃園 (TPE) ➔ 10:25 關西 (KIX)<br>座位: 16E、16F | 報到: T1 7號櫃台</p>
                <hr style="border:0; border-top:1px dashed #eee; margin:10px 0;">
                <div class="card-row">
                    <span><b>回程 (5/16 Fri)</b></span>
                    <span class="badge">IT210</span>
                </div>
                <p style="margin:0; font-size:0.9rem;">11:15 關西 (KIX) ➔ 13:10 桃園 (TPE)<br>座位: 10-E、10-F | 報到: T1 D號櫃台</p>
                <div class="note">⚠️ 手提行李限制：兩件合計不得超過 10kg，尺寸 54x38x23cm 以內。</div>
            </div>

            <div class="card">
                <h3><i class="fa-solid fa-car"></i> ORIX 租車資訊</h3>
                <p style="font-size: 0.9rem; margin-bottom: 5px;"><b>取車店鋪：</b> 大津駅南口店 (077-511-0555)<br>
                <b>租借期間：</b> 05/12 08:00 - 05/14 20:00<br>
                <b>預約番號：</b> W7201882<br>
                <b>租車金額：</b> 24,915円 (到店付款)</p>
                <div class="note">攜帶證件：駕照、日文譯本、護照。回程務必「滿油還車」並提供收據！</div>
            </div>
            
            <div class="card">
                <h3><i class="fa-solid fa-bus"></i> 天橋立高速巴士</h3>
                <p style="font-size: 0.9rem; margin-bottom: 5px;"><b>日期：</b> 05/10 07:20 - 18:00<br>
                <b>去程座位：</b> 04122037291 (3B/3A/4A)<br>
                <b>回程座位：</b> 04122037981 (2B/2A/3A)</p>
            </div>
        </section>

        <section id="hotel" class="tab-section">
            <div class="card">
                <h3><i class="fa-solid fa-hotel"></i> 1. 阪急龍仕柏飯店 (D1-D2)</h3>
                <p style="font-size: 0.9rem; margin: 5px 0;">Hotel Hankyu RESPIRE OSAKA<br>
                <b>Check-in:</b> 15:00 (9F櫃台) | <b>Check-out:</b> 12:00<br>
                <b>房型:</b> 標準三人房-禁菸 (Booking No. 4820992444)</p>
                <div class="note">交通：JR「大阪駅」3樓聯通橋 / 阪急「大阪梅田駅」</div>
            </div>
            <div class="card">
                <h3><i class="fa-solid fa-hotel"></i> 2. 京阪 京都八條口飯店 (D3-D4)</h3>
                <p style="font-size: 0.9rem; margin: 5px 0;">Hotel Keihan Kyoto Hachijoguchi<br>
                <b>Check-in:</b> 15:00 | <b>Check-out:</b> 11:00<br>
                <b>房型:</b> 標準三人房-禁菸 (Agoda No. 1531920464)</p>
                <div class="note">備註：有大浴場、提供冰棒。交通：JR「京都駅」八條東口。</div>
            </div>
            <div class="card">
                <h3><i class="fa-solid fa-hotel"></i> 3. 琵琶湖飯店 Biwako Hotel (D5)</h3>
                <p style="font-size: 0.9rem; margin: 5px 0;"><b>Check-in:</b> 15:00 | <b>Check-out:</b> 11:00<br>
                <b>房型:</b> 雙床房-禁菸 (Agoda No. 1534157384)</p>
                <div class="note">備註：露天溫泉。交通：JR「大津駅」北口轉接駁車。</div>
            </div>
            <div class="card">
                <h3><i class="fa-solid fa-hotel"></i> 4. 琵琶湖美爵溫泉度假酒店 (D6)</h3>
                <p style="font-size: 0.9rem; margin: 5px 0;">Grand Mercure Lake Biwa Resort<br>
                <b>房型:</b> 日式經典房-湖景 (Agoda No. 1527194640)</p>
                <div class="note">備註：免費暢飲。停車一樓先結帳 500円，30小時無限出入。</div>
            </div>
            <div class="card">
                <h3><i class="fa-solid fa-house"></i> 5. 樂天-獨棟式住宿 八幡堀 (D7)</h3>
                <p style="font-size: 0.9rem; margin: 5px 0;">Rakuten STAY HOUSE Hachimanbori<br>
                <b>Check-in:</b> 15:00 (前一天會寄發電子郵件密碼)<br>
                <b>房型:</b> 獨棟式三臥室別墅 (Agoda No. 1534066636)</p>
                <div class="note">備註：免費獨立停車格。包含廚房與洗衣設備。</div>
            </div>
            <div class="card">
                <h3><i class="fa-solid fa-hotel"></i> 6. 琵琶湖大津王子飯店 (D8)</h3>
                <p style="font-size: 0.9rem; margin: 5px 0;">LAKE BIWA OTSU PRINCE HOTEL<br>
                <b>Check-in:</b> 14:00 | <b>Check-out:</b> 11:00<br>
                <b>房型:</b> 湖景樓層-雙床房 (Agoda No. 1534294064)</p>
            </div>
            <div class="card">
                <h3><i class="fa-solid fa-hotel"></i> 7. NEST & RISE 大阪難波 (D9)</h3>
                <p style="font-size: 0.9rem; margin: 5px 0;"><b>Check-in:</b> 15:00 | <b>Check-out:</b> 10:00<br>
                <b>房型:</b> 標準雙人房-禁菸 (Agoda No. 1600275870)</p>
            </div>
        </section>

        <section id="info" class="tab-section">
            <div class="card">
                <h3><i class="fa-solid fa-shield-heart"></i> 保險與緊急聯絡</h3>
                <div class="card-row"><span><b>新安東京海上產險</b></span><span>0800-366-168</span></div>
                <p style="margin:0 0 10px 0; font-size:0.9rem; color:#555;">要保序號: 0014TRQ0422535 / 0014TRQ0422575<br>保險金額: 867元</p>
                
                <div class="card-row"><span><b>台北駐大阪辦事處</b></span><span>06-6227-8214</span></div>
                <p style="margin:0; font-size:0.9rem; color:#555;">平日 09:00 - 18:00<br>地點: 大阪市北区中之島二丁目三番一八号17F</p>
            </div>
            <div class="card">
                <h3><i class="fa-solid fa-cart-shopping"></i> 退稅重點指南</h3>
                <ul style="font-size: 0.9rem; padding-left: 20px; color: #555; margin:5px 0;">
                    <li>同一店家消費滿 <b>5,000日圓 (不含稅)</b> 以上即可退稅。</li>
                    <li>以免稅方式購物時需出示護照，現採電子化傳輸，出境海關需出示護照檢查。</li>
                    <li><b>消耗品 (化妝品、食品、藥品)</b>：會用特殊包裝密封，<b>離開日本前絕對不可拆封</b>，若拆封會被要求補稅。</li>
                    <li><b>一般物品 (衣物、家電)</b>：無包裝限制，可直接在日本使用。若與消耗品合併結帳，則視同消耗品不可拆封。</li>
                </ul>
            </div>
            <div class="card">
                <h3><i class="fa-solid fa-ticket"></i> EXPO 2025 萬博入場規定</h3>
                <ul style="font-size: 0.9rem; padding-left: 20px; color: #555; margin:5px 0;">
                    <li><b>全面無現金交易：</b>會場內不收現金，請準備 ICOCA、PAYPAY 或 VISA 信用卡。</li>
                    <li><b>禁止攜帶：</b>酒精飲料、腳架、行李箱。</li>
                    <li><b>建議攜帶：</b>零食、行動電源、防曬物品。</li>
                    <li>入場會進行安全檢查，請預留時間。</li>
                </ul>
            </div>
        </section>

    </main>

    <script>
        // 切換主選單
        function switchSection(sectionId) {
            document.querySelectorAll('.tab-section').forEach(el => el.classList.remove('active'));
            document.querySelectorAll('.nav-bar button').forEach(el => el.classList.remove('active'));
            
            document.getElementById(sectionId).classList.add('active');
            event.currentTarget.classList.add('active');
            document.querySelector('.content').scrollTop = 0;
        }

        // 切換行程天數
        function switchDay(dayId) {
            document.querySelectorAll('.day-content').forEach(el => el.classList.remove('active'));
            document.querySelectorAll('.day-btn').forEach(el => el.classList.remove('active'));
            
            document.getElementById(dayId).classList.add('active');
            event.currentTarget.classList.add('active');
        }
    </script>
</body>
</html>
