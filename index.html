<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>楓之谷遠征隊 - 自動報名與組隊系統</title>
    <style>
        body {
            font-family: "Microsoft JhengHei", Arial, sans-serif;
            background-color: #f4f6f9;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #fff;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        h1, h2 {
            text-align: center;
            color: #2c3e50;
        }
        .section {
            margin-bottom: 30px;
            padding: 15px;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            background-color: #fafbfc;
        }
        .section-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
        }
        .section-header h2 {
            margin: 0;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"], select {
            width: 100%;
            padding: 8px 12px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }
        .checkbox-group {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .checkbox-group label {
            font-weight: normal;
            background: #edf2f7;
            padding: 6px 12px;
            border-radius: 20px;
            cursor: pointer;
        }
        .checkbox-group input {
            margin-right: 5px;
        }
        button {
            background-color: #3182ce;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
        button:hover {
            background-color: #2b6cb0;
        }
        .btn-submit {
            width: 100%;
        }
        .btn-danger-sm {
            background-color: #e53e3e;
            color: white;
            padding: 4px 8px;
            font-size: 12px;
            border-radius: 4px;
        }
        .btn-danger-sm:hover {
            background-color: #c53030;
        }
        .btn-clear-all {
            background-color: #e53e3e;
            color: white;
            padding: 6px 12px;
            font-size: 13px;
        }
        .btn-clear-all:hover {
            background-color: #c53030;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
            background: white;
        }
        th, td {
            border: 1px solid #cbd5e0;
            padding: 8px 12px;
            text-align: center;
        }
        th {
            background-color: #e2e8f0;
        }
        .team-box {
            margin-top: 20px;
            padding: 15px;
            border-left: 5px solid #3182ce;
            background: #ebf8ff;
            border-radius: 4px;
        }
        .team-title {
            font-size: 18px;
            font-weight: bold;
            color: #2b6cb0;
            margin-bottom: 10px;
        }
        .flex-teams {
            display: flex;
            gap: 20px;
        }
        .flex-teams > div {
            flex: 1;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>🍁 楓之谷遠征隊報名與自動組隊系統</h1>

    <!-- 1. 玩家報名區 -->
    <div class="section">
        <h2>1. 填寫報名資料</h2>
        <form id="signupForm">
            <div class="form-group">
                <label for="playerName">玩家暱稱：</label>
                <input type="text" id="playerName" placeholder="請輸入暱稱" required>
            </div>
            <div class="form-group">
                <label for="playerJob">職業：</label>
                <select id="playerJob" required>
                    <option value="">-- 請選擇職業 --</option>
                    <option value="英雄">英雄</option>
                    <option value="黑騎士">黑騎士</option>
                    <option value="聖騎">聖騎</option>
                    <option value="刀賊">刀賊</option>
                    <option value="標賊">標賊</option>
                    <option value="箭神">箭神</option>
                    <option value="神射手">神射手</option>
                    <option value="主教">主教</option>
                    <option value="火毒">火毒</option>
                    <option value="冰雷">冰雷</option>
                    <option value="拳霸">拳霸</option>
                    <option value="槍神">槍神</option>
                </select>
            </div>
            <div class="form-group">
                <label>可參加時段（可複選）：</label>
                <div class="checkbox-group">
                    <label><input type="checkbox" name="times" value="週一 20:00"> 週一 20:00</label>
                    <label><input type="checkbox" name="times" value="週二 20:00"> 週二 20:00</label>
                    <label><input type="checkbox" name="times" value="週三 20:00"> 週三 20:00</label>
                    <label><input type="checkbox" name="times" value="週四 20:00"> 週四 20:00</label>
                    <label><input type="checkbox" name="times" value="週五 20:00"> 週五 20:00</label>
                    <label><input type="checkbox" name="times" value="週六 20:00"> 週六 20:00</label>
                    <label><input type="checkbox" name="times" value="週日 20:00"> 週日 20:00</label>
                </div>
            </div>
            <button type="button" class="btn-submit" onclick="addPlayer()">提交報名</button>
        </form>
    </div>

    <!-- 2. 已報名人員名單 -->
    <div class="section">
        <div class="section-header">
            <h2>2. 目前報名名單 (共 <span id="playerCount">0</span> 人)</h2>
            <button type="button" class="btn-clear-all" onclick="clearAllPlayers()">🗑️ 清空所有名單</button>
        </div>
        <table id="playerTable">
            <thead>
                <tr>
                    <th>序號</th>
                    <th>玩家暱稱</th>
                    <th>職業</th>
                    <th>可參加時段</th>
                    <th>操作</th>
                </tr>
            </thead>
            <tbody>
                <!-- 動態新增玩家 -->
            </tbody>
        </table>
    </div>

    <!-- 3. 自動組隊操作區 -->
    <div class="section">
        <h2>3. 選擇時段進行自動組隊</h2>
        <div class="form-group">
            <label for="filterTime">選擇目標組隊時段：</label>
            <select id="filterTime">
                <option value="週一">週一</option>
                <option value="週二">週二</option>
                <option value="週三">週三</option>
                <option value="週四">週四</option>
                <option value="週五">週五</option>
                <option value="週六" selected>週六</option>
                <option value="週日">週日</option>
            </select>
        </div>
        <button type="button" class="btn-submit" style="background-color: #38a169;" onclick="generateTeams()">開始自動組隊</button>
    </div>

    <!-- 4. 組隊結果呈現 -->
    <div id="resultsContainer"></div>

</div>

<script>
    // 預設名單
    let players = [
        { name: "玩家A", job: "主教", times: ["週六 20:00", "週日 20:00"] },
        { name: "玩家B", job: "英雄", times: ["週六 20:00"] },
        { name: "玩家C", job: "刀賊", times: ["週六 20:00", "週日 20:00"] },
        { name: "玩家D", job: "黑騎士", times: ["週六 20:00"] },
        { name: "玩家E", job: "黑騎士", times: ["週六 20:00"] },
        { name: "玩家F", job: "拳霸", times: ["週六 20:00"] },
        { name: "玩家G", job: "神射手", times: ["週六 20:00"] },
        { name: "玩家H", job: "標賊", times: ["週六 20:00", "週日 20:00"] },
        { name: "玩家I", job: "槍神", times: ["週六 20:00"] },
        { name: "玩家J", job: "火毒", times: ["週六 20:00"] },
        { name: "玩家K", job: "冰雷", times: ["週六 20:00"] },
        { name: "玩家L", job: "箭神", times: ["週六 20:00", "週日 20:00"] },
        { name: "玩家M", job: "英雄", times: ["週六 20:00"] },
        { name: "玩家N", job: "箭神", times: ["週六 20:00"] },
        { name: "1", job: "聖騎", times: ["週五 20:00"] },
        { name: "2", job: "聖騎", times: ["週四 20:00"] },
        { name: "3", job: "聖騎", times: ["週三 20:00"] },
        { name: "4", job: "聖騎", times: ["週二 20:00"] },
        { name: "5", job: "標賊", times: ["週五 20:00"] },
        { name: "6", job: "標賊", times: ["週四 20:00"] },
        { name: "7", job: "標賊", times: ["週三 20:00"] },
        { name: "8", job: "神射手", times: ["週二 20:00"] },
        { name: "9", job: "神射手", times: ["週五 20:00"] },
        { name: "10", job: "箭神", times: ["週四 20:00"] },
        { name: "11", job: "箭神", times: ["週三 20:00"] },
        { name: "12", job: "黑騎士", times: ["週二 20:00"] },
        { name: "Jinxian", job: "標賊", times: ["週一 20:00", "週日 20:00"] }
    ];

    updatePlayerTable();

    // 新增玩家
    function addPlayer() {
        const name = document.getElementById("playerName").value.trim();
        const job = document.getElementById("playerJob").value;
        const timeBoxes = document.querySelectorAll('input[name="times"]:checked');
        
        if (!name || !job) {
            alert("請填寫暱稱與職業！");
            return;
        }
        
        let selectedTimes = [];
        timeBoxes.forEach(box => selectedTimes.push(box.value));
        
        if (selectedTimes.length === 0) {
            alert("請至少選擇一個可參加時段！");
            return;
        }

        players.push({ name: name, job: job, times: selectedTimes });
        document.getElementById("signupForm").reset();
        updatePlayerTable();
        alert("報名成功！");
    }

    // 單筆刪除卡控
    function deletePlayer(index) {
        const pName = players[index].name;
        if (confirm(`⚠️ 確定要刪除「${pName}」的報名資料嗎？`)) {
            players.splice(index, 1);
            updatePlayerTable();
        }
    }

    // 全清空卡控（驗證字串改為 SMD）
    function clearAllPlayers() {
        if (players.length === 0) {
            alert("目前名單已經是空的！");
            return;
        }
        
        // 第一關：確認框
        if (confirm("⚠️ 警告：您確定要清空【所有】報名人員資料嗎？此操作無法復原！")) {
            // 第二關：手動輸入驗證字串 SMD
            const input = prompt("請在下方輸入大寫字母 SMD 以確認清空名單：");
            if (input === "SMD") {
                players = [];
                updatePlayerTable();
                document.getElementById("resultsContainer").innerHTML = "";
                alert("已成功清空所有報名資料！");
            } else if (input !== null) {
                alert("輸入驗證碼不正確，已取消清空操作。");
            }
        }
    }

    // 更新表格 UI
    function updatePlayerTable() {
        const tbody = document.querySelector("#playerTable tbody");
        tbody.innerHTML = "";
        
        players.forEach((p, idx) => {
            const tr = document.createElement("tr");
            tr.innerHTML = `
                <td>${idx + 1}</td>
                <td>${p.name}</td>
                <td>${p.job}</td>
                <td>${p.times.join(", ")}</td>
                <td><button type="button" class="btn-danger-sm" onclick="deletePlayer(${idx})">刪除</button></td>
            `;
            tbody.appendChild(tr);
        });
        
        document.getElementById("playerCount").innerText = players.length;
    }

    // 職業限制檢查
    function checkJobLimit(job, currentJobs) {
        let count = currentJobs.filter(j => j === job).length;
        if (["拳霸", "神射手", "標賊", "槍神", "主教", "火毒", "冰雷"].includes(job)) {
            return count < 1;
        } else if (["黑騎士", "英雄", "刀賊"].includes(job)) {
            return count < 2;
        }
        return true;
    }

    // 自動組隊 logic
    function generateTeams() {
        const filterTime = document.getElementById("filterTime").value;
        let eligible = players.filter(p => p.times.some(t => t.includes(filterTime)));
        
        if (eligible.length === 0) {
            alert(`在「${filterTime}」沒有任何玩家報名！`);
            return;
        }

        let isSelected = new Array(eligible.length).fill(false);
        let selectedList = [];

        // 優先抓 1 英雄、1 刀賊
        let heroIdx = eligible.findIndex((p, i) => !isSelected[i] && p.job === "英雄");
        if (heroIdx !== -1) {
            selectedList.push(eligible[heroIdx]);
            isSelected[heroIdx] = true;
        }
        
        let banditIdx = eligible.findIndex((p, i) => !isSelected[i] && p.job === "刀賊");
        if (banditIdx !== -1) {
            selectedList.push(eligible[banditIdx]);
            isSelected[banditIdx] = true;
        }

        // 填滿第一隊 (名額限制)
        for (let i = 0; i < eligible.length; i++) {
            if (selectedList.length >= 12) break;
            if (!isSelected[i]) {
                let currentJobs = selectedList.map(p => p.job);
                if (checkJobLimit(eligible[i].job, currentJobs)) {
                    selectedList.push(eligible[i]);
                    isSelected[i] = true;
                }
            }
        }

        // 剩餘玩家全數排隊
        for (let i = 0; i < eligible.length; i++) {
            if (!isSelected[i]) {
                selectedList.push(eligible[i]);
                isSelected[i] = true;
            }
        }

        renderResults(selectedList, filterTime, eligible.length);
    }

    // 渲染 UI 結果
    function renderResults(list, targetTime, totalCount) {
        const container = document.getElementById("resultsContainer");
        container.innerHTML = `<h2>【組隊結果 - ${targetTime}】 (符合總人數: ${totalCount} 人)</h2>`;

        let teamNum = 1;
        let playerIdx = 0;

        while (playerIdx < list.length) {
            let teamBox = document.createElement("div");
            teamBox.className = "team-box";

            let flexDiv = document.createElement("div");
            flexDiv.className = "flex-teams";

            let teamA = [], teamB = [];

            for (let i = 0; i < 6; i++) {
                if (playerIdx < list.length) teamA.push(list[playerIdx++]);
                if (playerIdx < list.length) teamB.push(list[playerIdx++]);
            }

            flexDiv.innerHTML = `
                <div>
                    <div class="team-title">--- 第 ${teamNum} 遠征隊 - 小隊 A (${teamA.length}人) ---</div>
                    ${generateTableHTML(teamA)}
                </div>
                <div>
                    <div class="team-title">--- 第 ${teamNum} 遠征隊 - 小隊 B (${teamB.length}人) ---</div>
                    ${generateTableHTML(teamB)}
                </div>
            `;

            teamBox.appendChild(flexDiv);
            container.appendChild(teamBox);
            teamNum++;
        }
    }

    function generateTableHTML(teamList) {
        if (teamList.length === 0) return "<p>無玩家</p>";
        let rows = teamList.map(p => `<tr><td>${p.name}</td><td>${p.job}</td></tr>`).join("");
        return `
            <table>
                <thead><tr><th>玩家暱稱</th><th>職業</th></tr></thead>
                <tbody>${rows}</tbody>
            </table>
        `;
    }
</script>

</body>
</html>
