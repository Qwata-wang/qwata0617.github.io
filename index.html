<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>有價證券信託-本金自益孳息他益試算器（2024)</title>
    <style>
        /* 隱藏數字輸入框的上下控制項 */
        input[type="number"] {
            -moz-appearance: textfield; /* Firefox */
            -webkit-appearance: none; /* Safari and Chrome */
            appearance: none;
        }
        input[type="number"]::-webkit-inner-spin-button,
        input[type="number"]::-webkit-outer-spin-button {
            -webkit-appearance: none;
            margin: 0;
        }
        body {
            font-family: Arial, sans-serif;
            background: #9CD9DF;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            width: 85%;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            margin: 20px;
        }
        .section {
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 5px;
        }
        .section-title {
            font-weight: bold;
            color: #FFFFFF;
            margin-bottom: 10px;
            font-size: 20px;
            text-align: center;
            padding: 10px;
            border-radius: 5px;
        }
        .section:nth-of-type(1) {
            background-color: #F2F2F2;
        }
        .section:nth-of-type(1) .section-title {
            background-color: #e55347;
        }
        .section:nth-of-type(2) {
            background-color: #F2F2F2;
        }
        .section:nth-of-type(2) .section-title {
            background-color: #e55347;
        }
        .section:nth-of-type(3) {
            background-color: #D9EAF7;
        }
        .section:nth-of-type(3) .section-title {
            background-color: #267596;
        }
        label {
            display: block;
            margin: 10px 0 5px;
            font-weight: bold;
            color: #333;
        }
        .input-group {
            display: flex;
            justify-content: space-between;
            gap: 10px;
        }
        .input-unit-wrapper {
            display: flex;
            align-items: center;
            gap: 5px;
        }
        input[type="text"], input[type="number"], input[type="tel"] {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
            box-sizing: border-box;
        }
        .unit {
            font-size: 16px;
            color: #333;
        }
        button {
            width: 100%;
            padding: 12px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        .stock-button {
            width: 90px; /* 設置按鈕的寬度 */
        }
        button:hover {
            background-color: #45a049;
        }
        .result {
            margin-top: 20px;
            text-align: center;
            color: #333;
            font-size: 16px;
        }
        .button-group {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }
        table {
            font-size: 16px;
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 19px;
            }
            label, input, button {
                font-size: 14px;
            }
            button {
                padding: 10px;
            }
            .input-group {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>有價證券信託-本金自益孳息他益試算器（2024）</h1>
        <p style="color: #000000; background-color: #F7ECDF; padding: 10px; font-size: 15px; border-radius: 5px; border-left: 5px solid #E4232C;">
            ※ 本試算表的計算結果僅供參考，實際應納稅額仍依據當年度個人贈與情況決定。
        </p>
        <!-- 信託規劃基本資料 -->
        <div class="section">
            <div class="section-title">信託規劃基本資料</div>
            <form id="trustForm">
                <label for="clientName">客戶姓名</label>
                <input type="text" id="clientName" name="clientName" placeholder="輸入客戶姓名" required>

                <div class="input-group">
                    <div style="flex: 1;">
                        <label for="trustShares"><span style="color: red;">*</span> 交付信託股票張數</label>
                        <div class="input-unit-wrapper">
                            <input type="number" id="trustShares" name="trustShares" placeholder="輸入股票張數" required>
                            <span class="unit">張</span>
                        </div>
                    </div>
                    <div style="flex: 1;">
                        <label for="trustYears"><span style="color: red;">*</span> 信託規劃年數 (至少３年)</label>
                        <div class="input-unit-wrapper">
                            <input type="number" id="trustYears" name="trustYears" placeholder="輸入信託年數" required>
                            <span class="unit">年</span>
                        </div>
                    </div>
                </div>

              <div class="input-group" style="display: flex; align-items: flex-start; gap: 10px;">
    <!-- 交付股票代號部分 -->
                <div style="flex: 1;">
                    <label for="stockCode"><span style="color: red;">*</span> 交付股票代號</label>
                    <div class="input-unit-wrapper" style="display: flex; align-items: center; gap: 10px;">
                        <input type="number" id="stockCode" name="stockCode" placeholder="輸入股票代號" required style="width: 180px;">
                        <button type="button" class="stock-button" onclick="window.open('https://tw.stock.yahoo.com/', '_blank')" style="flex-shrink: 0;">查詢股價</button>
                    </div>
                </div>
                
                <!-- 股價部分 -->
                <div style="flex: 1;">
                    <label for="stockPrice" style="margin-bottom: 5px; display: block;"><span style="color: red;">*</span> 股價</label>
                    <div class="input-unit-wrapper" style="display: flex; align-items: center;">
                        <input type="number" id="stockPrice" name="stockPrice" placeholder="輸入股價" required>
                        <span class="unit" style="margin-left: 2px;">元</span>
                    </div>
                </div>
            </div>
            </form>
        </div>

<!-- 預估未來股價、配股配息 -->
<div class="section">
    <div class="section-title">預估未來股價、配股配息</div>
    <div class="input-group">
        <div style="flex: 1;">
            <label for="futureStockPrice"><span style="color: red;">*</span> 預估未來股價</label>
            <div class="input-unit-wrapper">
                <input type="number" id="futureStockPrice" name="futureStockPrice" placeholder="輸入預估未來股價" required>
                <span class="unit">元</span>
            </div>
        </div>
        <div style="flex: 1;">
            <label for="futureEarningsShares"><span style="color: red;">*</span> 預估未來盈餘配股</label>
            <div class="input-unit-wrapper">
                <input type="number" id="futureEarningsShares" name="futureEarningsShares" placeholder="輸入預估盈餘配股" required>
                <span class="unit">元</span>
            </div>
        </div>
        <div style="flex: 1;">
            <label for="futureCashDividend"><span style="color: red;">*</span> 預估未來現金股利</label>
            <div class="input-unit-wrapper">
                <input type="number" id="futureCashDividend" name="futureCashDividend" placeholder="輸入預估現金股利" required>
                <span class="unit">元</span>
            </div>
        </div>
    </div>
    <div style="width: 100%; text-align: left; margin-top: 10px; color: #333; font-size: 14px;">
        ※假設辦理信託期間，每年配股、配息率維持相同。
    </div>
</div>

<!-- 內部人資訊 -->
<div class="section">
    <div class="section-title">內部人資訊</div>
    <div class="input-group">
        <div style="flex: 1;">
            <label for="initialHolding">選任時持股</label>
            <div class="input-unit-wrapper" style="display: flex; align-items: center;">
                <input type="number" id="initialHolding" name="initialHolding" placeholder="輸入選任時持股" required oninput="updateRetainedAndMaxShares()" style="width: 100%;">
                <span class="unit" style="margin-left: 2px;">股</span>
            </div>
        </div>
        <div style="flex: 1;">
            <label for="retainedShares">應保留股數 (自動計算)</label>
            <div class="input-unit-wrapper" style="display: flex; align-items: center;">
                <input type="number" id="retainedShares" name="retainedShares" readonly style="width: 100%;">
                <span class="unit" style="margin-left: 2px;">股</span>
            </div>
        </div>
    </div>

    <div class="input-group" style="margin-top: 10px;">
        <div style="flex: 1;">
            <label for="currentHolding">目前持有股數</label>
            <div class="input-unit-wrapper" style="display: flex; align-items: center;">
                <input type="number" id="currentHolding" name="currentHolding" placeholder="輸入目前持有股數" required oninput="updateRetainedAndMaxShares()" style="width: 100%;">
                <span class="unit" style="margin-left: 2px;">股</span>
            </div>
        </div>
        <div style="flex: 1;">
            <label for="maxAvailableShares">最多可承做股數 (自動計算)</label>
            <div class="input-unit-wrapper" style="display: flex; align-items: center;">
                <input type="number" id="maxAvailableShares" name="maxAvailableShares" readonly style="width: 100%;">
                <span class="unit" style="margin-left: 2px;">股</span>
            </div>
        </div>
    </div>
    <div style="width: 100%; text-align: left; margin-top: 10px; color: #333; font-size: 14px;">
        ※交付信託股數應<=內部人最多可承做股數。
    </div>
</div>
        <!-- 送出資料按鈕 -->
        <div class="button-group">
            <button type="button" onclick="validateAndCalculateResults()">送出資料</button>
        </div>

        <div class="result" id="result"></div>
    </div>

    <form id="trustForm" onsubmit="event.preventDefault(); validateAndCalculateResults();">
        <!-- 其餘的表單輸入元素 -->
    </form>

    <script>
        function validateAndCalculateResults() {
            // 檢查必填的欄位是否都有值
            const requiredFields = [
                { id: 'trustShares', name: '交付信託股票張數' },
                { id: 'trustYears', name: '信託規劃年數 (至少 3 年)' },
                { id: 'stockCode', name: '交付股票代號' },
                { id: 'stockPrice', name: '股價' },
                { id: 'futureStockPrice', name: '預估未來股價' },
                { id: 'futureEarningsShares', name: '預估未來盈餘配股' },
                { id: 'futureCashDividend', name: '預估未來現金股利' }
            ];

            for (let field of requiredFields) {
                const value = document.getElementById(field.id).value;
                if (!value) {
                    alert(`請填寫 ${field.name}`);
                    return; // 停止執行，直到所有欄位都有值
                }
            }

            // 所有必填項目都有值，進行計算
            calculateResults();
        }

        function calculateResults() {
            // 收集用戶輸入的數據
            const trustShares = parseFloat(document.getElementById('trustShares').value) || 0;
            const trustYears = parseFloat(document.getElementById('trustYears').value) || 0;
            const stockPrice = parseFloat(document.getElementById('stockPrice').value) || 0;
            const futureEarningsShares = parseFloat(document.getElementById('futureEarningsShares').value) || 0;
            const futureCashDividend = parseFloat(document.getElementById('futureCashDividend').value) || 0;
            const futureStockPrice = parseFloat(document.getElementById('futureStockPrice').value) || 0;

            // 信託本金計算
            const trustPrincipal = trustShares * 1000 * stockPrice;

            // 信託本金現值
            const trustPrincipalPV = trustPrincipal / Math.pow(1 + 0.01725, trustYears);

            // 計算應納贈與稅的相關數據
            const E5 = trustPrincipal - trustPrincipalPV;
            const F5 = 2440000;

            let giftTax;
            if (E5 - F5 <= 25000000) {
                giftTax = (E5 - F5) * 0.1;
            } else if (E5 - F5 <= 50000000) {
                giftTax = (E5 - F5) * 0.15 - 1250000;
            } else {
                giftTax = (E5 - F5) * 0.2 - 3750000;
            }
            giftTax = giftTax < 0 ? 0 : Math.round(giftTax);

            // 每年股利收入
            const annualDividendIncome = Math.floor(trustShares * 1000 * futureEarningsShares / 10) * futureStockPrice +
                                         Math.floor(trustShares * 1000 * futureCashDividend);
            const totalDividendIncome = annualDividendIncome * trustYears;

            // 節省贈與稅計算
            let firstYearTaxSavings, subsequentYearsTaxSavings;
            if (annualDividendIncome <= 25000000) {
                firstYearTaxSavings = annualDividendIncome * 0.1 - giftTax;
                subsequentYearsTaxSavings = annualDividendIncome * 0.1 * (trustYears - 1);
            } else if (annualDividendIncome <= 50000000) {
                firstYearTaxSavings = annualDividendIncome * 0.15 - 1250000 - giftTax;
                subsequentYearsTaxSavings = (annualDividendIncome * 0.15 - 1250000) * (trustYears - 1);
            } else {
                firstYearTaxSavings = annualDividendIncome * 0.2 - 3750000 - giftTax;
                subsequentYearsTaxSavings = (annualDividendIncome * 0.2 - 3750000) * (trustYears - 1);
            }

            const F38 = firstYearTaxSavings + subsequentYearsTaxSavings;

            // 結果顯示
            let maxTaxSavingsText;
            if (F38 > 0) {
                maxTaxSavingsText = `<span style="font-size: larger;">最多可省下 ${Math.round(F38).toLocaleString()} 元</span>`;
            } else {
                maxTaxSavingsText = `<span style="font-size: larger;">最多可省下 0 元</span>`;
            }

            const resultData = `
                <table style="width: 90%; margin: 0 auto; border-collapse: collapse; margin-top: 20px; border: 1px solid #D3D3D3;">
                    <tr style="background-color: #F7ECDF; border-bottom: 1px solid #D3D3D3;">
                        <td style="width: 57%; padding: 10px 15px; font-weight: bold; color: #333; text-align: left;">信託本金</td>
                        <td style="width: 43%; padding: 10px 15px; text-align: right; background-color: #FFFFFF; color: #333;">${trustPrincipal.toLocaleString()} 元</td>
                    </tr>
                    <tr style="background-color: #F7ECDF; border-bottom: 1px solid #D3D3D3;">
                        <td style="padding: 10px 15px; font-weight: bold; color: #333; text-align: left;">信託期間</td>
                        <td style="padding: 10px 15px; text-align: right; background-color: #FFFFFF; color: #333;">${trustYears} 年</td>
                    </tr>
                    <tr style="background-color: #F7ECDF; border-bottom: 1px solid #D3D3D3;">
                        <td style="padding: 10px 15px; font-weight: bold; color: #333; text-align: left;">預估股利收入</td>
                        <td style="padding: 10px 15px; text-align: right; background-color: #FFFFFF; color: #333;">${totalDividendIncome.toLocaleString()} 元</td>
                    </tr>
                    <tr style="background-color: #F7ECDF; border-bottom: 1px solid #D3D3D3;">
                        <td style="padding: 10px 15px; font-weight: bold; color: #333; text-align: left;">成立信託應納贈與稅</td>
                        <td style="padding: 10px 15px; text-align: right; background-color: #FFFFFF; color: #333;">${giftTax.toLocaleString()} 元</td>
                    </tr>
                    <tr style="background-color: #e55347; color: #FFFFFF;">
                        <td colspan="2" style="padding: 15px; text-align: center; font-weight: bold;">${maxTaxSavingsText}</td>
                    </tr>
                </table>
            `;
            document.getElementById('result').innerHTML = `<h2>查詢結果</h2>${resultData}`;
        }

        function updateRetainedAndMaxShares() {
            const initialHolding = parseFloat(document.getElementById('initialHolding').value) || 0;
            const currentHolding = parseFloat(document.getElementById('currentHolding').value) || 0;

            // 計算應保留股數，公式：IF(ISBLANK(I4), 0, ROUND(I4/2+1, 0))
            const retainedShares = initialHolding ? Math.round(initialHolding / 2 + 1) : 0;
            document.getElementById('retainedShares').value = retainedShares;

            // 計算最多可承做股數，公式：IF(I8-I6<0, 0, I8-I6)
            const maxAvailableShares = Math.max(0, currentHolding - retainedShares);
            document.getElementById('maxAvailableShares').value = maxAvailableShares;
        }
    </script>
</body>
</html>
