<!-- 產品／專案：allview_today_cis｜法人／事業體：AllView／全視界（完整法定名稱 [待確認]）｜日期：2026-11-11（Asia/Taipei）｜草稿 v0.3 -->
# allview_today_cis
全視界數位內容有限公司 (Allview.today) 官方網站架構與企業識別系統 (CIS) 
# 全視界數位內容有限公司 (Allview.today)
## 官方網站架構與企業識別系統 (CIS) 規範白皮書
**版本：** v1.0.0 GA  
**所屬體系：** 「四即一・一即四」全域事業體拓樸控制平面  
**PMO 專案代號：** `C1-AV-CORP` (`allview-today-corporate`)  
**關聯預售線：** `C2-AV-IMN` (多語行銷) | `C2-AV-FHS` (FHE 隱私社群) | `C2-AV-MWS` (商場兵推)

---

## 目錄
1. [戰略定位與系統拓樸](#一戰略定位與系統拓樸)
2. [CIS 企業識別規範：臺灣意象與國際元素融合](#二cis-企業識別規範臺灣意象與國際元素融合)
   - 2.1 設計哲學：【山海稜鏡・映現萬象】
   - 2.2 核心標誌 (Logo) 向量幾何構成
   - 2.3 品牌色彩系統 (Formosa & Global Palette)
   - 2.4 八大語系文字排印 (Typography) 與 Slogan 規範
   - 2.5 實體與數位事務識別規範 (Brand Assets)
3. [官網全景資訊架構 (Information Architecture)](#三官網全景資訊架構-information-architecture)
   - 3.1 頁面層級與導航拓樸
   - 3.2 頂部導航與八語即時在地化切換
   - 3.3 首頁主視覺 (Hero Section) 互動動態
   - 3.4 萬象文化對比實驗室 (Culture Sandbox - 寓教於樂模組)
   - 3.5 全景守護技術底座 (AI Security & Topology)
4. [三大旗艦產品預售整合模組 (Presale Portals)](#四大旗艦產品預售整合模組-presale-portals)
5. [工程交付、部署與 PMO 規範](#五工程交付部署與-pmo-規範)
   - 5.1 Repository 文件骨架標準
   - 5.2 角色權限與 Email Alias 控制
   - 5.3 七道 QA 驗收閘門 (Quality Gates)
   - 5.4 部署架構與安全原則

---

## 一、戰略定位與系統拓樸

在「四即一、一即四」全域事業體阿米巴架構中，全視界（Allview.today）承擔著**文化傳播、宗教數位轉譯、意識形態交流與全球軟實力輸出**的對外旗艦窗口職責。

```
              ┌────────────────────────────────────────┐
              │    Wonderland Center (平台經濟/金流)    │
              │   國家主權基金連結 / 群眾募資與群眾發包   │
              └───────────────────┬────────────────────┘
                                  │
         ┌────────────────────────┼────────────────────────┐
         ▼                        ▼                        ▼
┌─────────────────┐      ┌─────────────────┐      ┌─────────────────┐
│ AEGIS.expert    │      │ Allview.today   │      │ NGO & 公益聚落   │
│ FHE / 善AI聯盟  │◄────►│ 文化/宗教/媒體  │◄────►│ 惜食運送/戰後重建│
│ 底層安全護城河   │      │ 軟實力輸出窗口   │      │ 分散式議題專案   │
└─────────────────┘      └─────────────────┘      └─────────────────┘
```

### 1.1 核心使命
* **文明互照，消弭斷層**：利用新型 AI 科技為跨國閱聽眾具體轉譯文化、宗教與意識形態，提供跨國界文化自然對照、相互尊重的數位平台。
* **軟實力寓教於樂輸出**：打破傳統宣傳教條，以趣味互動、生成式視覺繪卷與雙向對照實驗室，讓各國主權文化與在地精神展現包容度與滲透力。
* **阿米巴原子化單元協同**：作為標準阿米巴單位，平時執行在地文化數位化營運；動態徵召時，支援全域資源調度（人力、算力與內容轉發）。

---

## 二、CIS 企業識別規範：臺灣意象與國際元素融合

### 2.1 設計哲學：【山海稜鏡・映現萬象】
* **臺灣意象 (Formosa Identity)**：
  * **中央山脈脊樑線**：象徵臺灣島嶼的堅毅包容、深厚多元文化底蘊，以及支撐全景守護的穩固架構。
  * **太平洋海潮波浪**：象徵海洋國度向世界八方敞開胸懷、生生不息的創新活力（萬象生生）。
* **國際科技元素 (Global Tech & Topology)**：
  * **光學八角稜鏡 (Octagonal Prism)**：以光學折射象徵 AI 科技，將單一文化的白光解析為絢麗的八方光譜。
  * **拓樸神經光點網格**：代表全球跨域阿米巴節點互聯互通，形成去中心化的安全文化網絡。

### 2.2 核心標誌 (Logo) 向量幾何構成
```
                /\             ─── 八角稜鏡頂點 (Zenith Node)
               /  \
             /  /\  \          ─── 中央山脈抽象幾何 (Formosa Peak)
            /  /  \  \
           /  /____\  \        ─── 視界之眼 (Allview Optical Core)
          /  (  /\  )  \
         /____\/  \/____\      ─── 太平洋洋流弧線 (Ocean Current Vectors)
              \    /
               \  /            ─── 匯聚節點 (Synergy Convergence)
                \/
```
* **幾何比例**：以黃金比例 $\Phi \approx 1.618$ 切割山脊線與八角稜鏡外切圓。
* **標準標誌淨空區 (Safe Margin)**：標誌周圍保留不小於 Logo 高度 $0.25H$ 的純淨留白區，禁止任何文字或雜訊侵入。
* **最小適用尺寸**：印刷品寬度不小於 $15\text{ mm}$；數位螢幕寬度不小於 $64\text{ px}$。

### 2.3 品牌色彩系統 (Formosa & Global Palette)

| 色彩屬性 | 色彩名稱 | HEX | RGB | CMYK | 意涵與使用情境 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Primary 1** | **臺灣山海青藍**<br>(Formosa Ocean & Peak Blue) | `#0D3B66` | `(13, 59, 102)` | `C95 M75 Y35 K25` | 象徵中央山脈與深邃海洋，高階信任感、全景守護的底座主色。 |
| **Primary 2** | **萬象晨曦金橙**<br>(Dawn Aura Gold) | `#F4A261` | `(244, 162, 97)` | `C0 M45 Y70 K0` | 象徵晨曦拂曉、萬象生生的溫暖、文化包容性與心靈溫度。 |
| **Secondary 1** | **玉山生機翡翠綠**<br>(Formosa Jade Green) | `#2A9D8F` | `(42, 157, 143)` | `C80 M20 Y50 K0` | 象徵臺灣山林生態與阿米巴自繁衍生命力，用於互動亮點與綠色通道。 |
| **Secondary 2** | **玄武岩墨黑**<br>(Basalt Slate) | `#264653` | `(38, 70, 83)` | `C85 M60 Y55 K40` | 象徵澎湖玄武岩地質，權威文字、邊框與極深色背景。 |
| **Neutral** | **鈦晶白**<br>(Titanium White) | `#F8F9FA` | `(248, 249, 250)` | `C1 M1 Y1 K0` | 科技感純淨留白，提供寬裕的閱讀空間。 |

### 2.4 八大語系文字排印 (Typography) 與 Slogan 規範

#### 字體規範矩陣
* **西文/法/德/西語**：標題使用 `Inter Display` / `Montserrat`；內文使用 `Inter` / `Roboto`。
* **繁體中文 (臺灣)**：標題使用 `思源黑體 (Source Han Sans TW) Heavy` / `凝書體風格`；內文使用 `思源黑體 Regular`。
* **簡體中文**：標題使用 `思源黑體 (Source Han Sans SC) Bold`；內文使用 `思源黑體 Regular`。
* **日文 (日本語)**：標題使用 `Noto Sans JP Bold`；內文使用 `Noto Sans JP Regular`。
* **韓文 (한국어)**：標題使用 `Noto Sans KR Bold`；內文使用 `Noto Sans KR Regular`。

#### 八語官方精神宣言 (Official Multilingual Slogans)
1. **繁體中文 (Traditional Chinese)**  
   * 主標語：*「視通山海，心映萬象」*  
   * 理念句：*「以新型 AI 科技轉譯信仰與文化，用故事拉近世界距離。」*
2. **簡體中文 (Simplified Chinese)**  
   * 主标语：*「视通万象，心映文明」*  
   * 理念句：*「以安全 AI 驱动跨文化理解与全球对话平台。」*
3. **英文 (English)**  
   * Master Slogan: *“All Views, All Cultures, One World.”*  
   * Mission statement: *“Mirroring Civilizations and Faiths through Safe AI Innovations.”*
4. **日文 (Japanese)**  
   * スローガン：*「万象を映し、世界を繋ぐ」*  
   * ステートメント：*「最先端のAI技術で紡ぐ、多文化共生と心の対話。」*
5. **韓文 (Korean)**  
   * 슬로건: *「만상을 비추고 세계를 잇다」*  
   * 비전: *「차세대 AI 기술로 열어가는 다문화 공존과 영적 대화의 장.」*
6. **西班牙文 (Spanish)**  
   * Eslogan: *“Todas las Visiones, Un Solo Mundo.”*  
   * Misión: *“Reflejando civilizaciones y espiritualidades con IA avanzada y segura.”*
7. **法文 (French)**  
   * Slogan: *« Toutes les Visions, Un Seul Monde. »*  
   * Vision: *« Faire résonner les cultures et les fois grâce à l'intelligence artificielle. »*
8. **德文 (German)**  
   * Slogan: *„Alle Horizonte, Eine Welt.“*  
   * Leitbild: *„Kultur- und Ideologiedialog durch vertrauenswürdige KI.“*

### 2.5 實體與數位事務識別規範 (Brand Assets)

```
┌───────────────────────────────────────┐   ┌─────────────────────────────────────────┐
│ 全視界數位內容有限公司                      │   │ ALLVIEW.TODAY                           │
│ Allview.today Digital Content Inc.    │   │                                         │
│                                       │   │ [ Formosa Ocean Gradient Waves ]        │
│ 林書懷 (Shu-Huai Lin)                 │   │                                         │
│ 跨文化數位架構總監                      │   │ ┌───────┐  FHE-Secured Identity Key     │
│                                       │   │ │ QR-   │  DID: tw.allview.id/8f9a2b        │
│ E: shu-huai.lin@allview.today         │   │ │ CODE  │  PGP Fingerprint Verified       │
│ W: https://allview.today              │   │ └───────┘  All Views, All Cultures.     │
└───────────────────────────────────────┘   └─────────────────────────────────────────┘
  [名片正面：山海青底 + 晨曦金燙印 Logo]        [名片背面：八語微縮矩陣 + 匿名公開密鑰 QR]
```

* **信封系統 (Envelope Suite)**：信封摺口處以臺灣東海岸浪潮等高線作光學全息防偽壓印，內部底紋為八語文字交織微縮印花。
* **簡報母片 (Hero Master Deck 16:9)**：
  * 首頁母片：中央為 3D 旋轉八角稜鏡，外環帶有即時脈衝光點網絡。
  * 內容頁：左側保留 $35\%$ 寬度呈現「全景守護」架構指引，右側為萬象內容發布卡片。

---

## 三、官網全景資訊架構 (Information Architecture)

### 3.1 頁面層級與導航拓樸
```
Allview.today 官方網站
├── 1.0 首頁 (Hero & Allview Hub)
│   ├── 1.1 動態山海稜鏡 主視覺
│   ├── 1.2 即時跨文化脈動摘要
│   └── 1.3 快速入口（預售、文化實驗室、合作）
├── 2.0 萬象聚落 (Culture Sandbox & Media)
│   ├── 2.1 跨國界文化對比實驗室
│   ├── 2.2 宗教與民俗數位轉譯頻道
│   └── 2.3 寓教於樂軟實力影音庫
├── 3.0 全景守護 (Security & Architecture)
│   ├── 3.1 善 AI 聯盟拓樸與資料主權架構
│   ├── 3.2 FHE/HE 隱私防護運作白皮書
│   └── 3.3 全域阿米巴單元協調協定
├── 4.0 旗艦產品預售 (Presale Ecosystem)
│   ├── 4.1 多語國際行銷網絡 (`allview-intl-marketing-network-presale`)
│   ├── 4.2 FHE 匿名不否認論壇 (`allview-fhe-social-presale`)
│   └── 4.3 文化商場沙盤推演 (`allview-market-simulation-presale`)
├── 5.0 合作夥伴與發包 (Collaborate & Crowdsourcing)
│   ├── 5.1 對接 Wonderland Center 發包需求
│   └── 5.2 全球在地文化轉譯志工登記
└── 6.0 法律與合規 (Legal & Governance)
    ├── 6.1 公司法定登記揭露 (Legal Entity Transparency)
    ├── 6.2 隱私權政策與 Cookie 政策 (PDPA / GDPR / AI Act)
    └── 6.3 資訊安全與弱點回報通道
```

### 3.2 頂部導航與八語即時在地化切換
* **語言選擇羅盤 (Language Compass)**：
  * 點擊導航列右上角 `🌐 Language`，展開八向羅盤互動切換器。
  * 切換後全站路由動態對應：
    * 繁中：`allview.today/zh-tw/`
    * 簡中：`allview.today/zh-cn/`
    * 英文：`allview.today/en/`
    * 日文：`allview.today/ja/`
    * 韓文：`allview.today/ko/`
    * 西文：`allview.today/es/`
    * 法文：`allview.today/fr/`
    * 德文：`allview.today/de/`
* **文化在地化自適應**：不僅是文字翻譯，切換語言後 Hero 主圖的故事軸心將自動調整為對應語系與全球文化交流的第一視角。

### 3.3 首頁主視覺 (Hero Section) 互動動態
* **視覺構成**：
  * 底層：暗山海青色（`#0D3B66`）深邃空間，隱現臺灣中央山脈等高線拓樸。
  * 中層：WebGL 實時渲染的「八角光學稜鏡」，射入一道單一光束，折射出代表 8 種語言與全球數十個主權文化的光譜光帶。
  * 上層：雙核心行動呼籲按鈕（CTA）：
    * `[ 進入文化對比實驗室 | Explore Culture Sandbox ]`（導向 2.1）
    * `[ 參與產品預售 | Discover Presales ]`（導向 4.0）

### 3.4 萬象文化對比實驗室 (Culture Sandbox - 寓教於樂模組)
* **核心機制**：
  * 訪客可在互動面板中選取特定「生活或精神命題」（例如：*成年禮節*、*感恩慶典*、*生死哲思*、*時間觀念*）。
  * 雙軌或三軌並排展示：左側為臺灣或東亞在地觀點，右側為南歐、西非、拉美或中東觀點。
  * 由 Allview AI 轉譯引擎自動生成對照漫畫、哲學寓言或情境模擬音頻，讓閱聽眾直觀體會文明異同，促進深刻包容。

### 3.5 全景守護技術底座 (AI Security & Topology)
* **主權資料護城河**：
  * 清晰呈現全視界與母體 **AEGIS.expert** 的技術對接：使用完全同態加密（FHE）技術處理跨國敏感文化與意識形態數據。
  * **承諾原則**：不進行無授權文化剽竊、不強制集中文化詮釋權、原始宗教哲思資料不上未授權雲端。

---

## 四、三大旗艦產品預售整合模組 (Presale Portals)

官網首頁及 `/presale/` 專區無縫嵌入第一階段三大主力預售項目，並對齊 PMO 規範：

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                           全視界三大旗艦產品預售入口                          │
├───────────────────────┬─────────────────────────┬───────────────────────────┤
│ C2-AV-IMN             │ C2-AV-FHS               │ C2-AV-MWS                 │
│ 國際行銷網絡多語服務    │ FHE 匿名無法否認社群     │ 商場沙盤推演兵推系統       │
│ Allview Marketing     │ Allview FHE Social      │ Allview Market Sandbox    │
├───────────────────────┼─────────────────────────┼───────────────────────────┤
│ 針對跨國政府/品牌/NGO │ 針對思想領袖、跨文化對話 │ 針對跨國行銷、公關、文化出 │
│ 提供一鍵鋪開全球傳播  │ 提供高保證匿名、演講、   │ 海進行意識形態動態模擬與   │
│ 的多語在地轉譯與傳播  │ 不可否認論壇之專用軟體   │ 商業推演服務               │
├───────────────────────┼─────────────────────────┼───────────────────────────┤
│ 交付物：SaaS/API/管理 │ 交付物：桌面/Web 雙重版  │ 交付物：推演引擎/報告套件 │
│ [ 探索預售詳情 ➔ ]     │ [ 探索預售詳情 ➔ ]       │ [ 探索預售詳情 ➔ ]        │
└───────────────────────┴─────────────────────────┴───────────────────────────┘
```

1. **國際行銷網路多語化在地服務 (`allview-intl-marketing-network-presale`)**：
   * **痛點**：跨國行銷常因翻譯生硬或踩踏文化禁忌而受挫。
   * **解法**：以在地化語意模型與文化禁忌偵測機制，協助臺灣及各國優質品牌走向八大語系市場。
2. **具備 FHE 的社群（SMS）可匿名又無法否認軟體 (`allview-fhe-social-presale`)**：
   * **痛點**：敏感宗教、哲思與政治議題在現有社群易遭肉搜與言論審查。
   * **解法**：在密文下驗證發言資格，提供不可篡改亦不可否認的言論存證，但保護發言者物理身分。
3. **商場沙盤推演與文化兵推系統 (`allview-market-simulation-presale`)**：
   * **痛點**：產品進入跨國新市場前缺乏對當地文化反應的預判。
   * **解法**：阿米巴模擬器建立虛擬閱聽眾群體，預演各類公關與文化行銷事件的反饋。

---

## 五、工程交付、部署與 PMO 規範

依據 PMO 控制表與微軟雲端工程實務，全視界官網與各產品預售站點嚴格區分「代碼控制面」與「正式商用金流面」。

### 5.1 Repository 文件骨架標準
所有由 Allview.today 負責的 Repository（包括 `C1-AV-CORP` 及相關預售與應用端）必須維持以下標準目錄：

```
allview-today-corporate/
├── README.md                 # 專案概觀、八語 Slogan、快速預覽指引
├── ARCHITECTURE.md           # 系統拓樸、動態渲染架構、CIS 資源對照
├── REQUIREMENTS.md           # FR/NFR 功能與非功能性需求追蹤碼
├── QA-ACCEPTANCE.md          # 七道 QA 閘門測試檢驗標準
├── TEST-PLAN.md              # 跨語系、響應式、效能自動化測試腳本
├── DEPLOYMENT.md             # Azure Static Web Apps CI/CD 流程
├── SECURITY.md               # 漏洞通報 SOP 與加密金鑰隔離規範
├── CONTRIBUTING.md           # Crowdsourcing 開發協作標準
├── CHANGELOG.md              # 版本演進紀錄
├── cis/                      # 向量 Logo、母片模板、色票設定檔
│   ├── logos/
│   ├── typography/
│   └── templates/
├── docs/                     # 跨文化轉譯字典、API 規格書
└── .github/
    ├── CODEOWNERS            # 責任分派
    ├── pull_request_template.md
    └── ISSUE_TEMPLATE/
```

### 5.2 角色權限與 Email Alias 控制
遵循「人與角色分離」原則，成員透過 Team 進行權限管理，信箱使用特定專案別名：

| 專案別名 (Alias) | 職責與用途 | 預設權限 |
| :--- | :--- | :--- |
| `dev-allview-today-corporate@allview.today` | 主力開發引導、架構審查、Actions 配置 | Write / Maintain |
| `collab-allview-today-corporate@allview.today` | Crowdsourcing 協同開發者、文化內容提供 | Write (via PR) |
| `qa-allview-today-corporate@allview.today` | 跨語系測試、CIS 合規驗收、自動化測試 | Triage / Write |
| `admin-allview-today-corporate@allview.today` | 組織管理、發布審批、DNS 與安全設定 | Admin |

### 5.3 七道 QA 驗收閘門 (Quality Gates)
本專案在發布至正式環境前，必須在 `QA-ACCEPTANCE.md` 中全數通過以下七道閘門驗證：

```
Gate 1: Scope Ready
  └─ 確認八語文案完整齊備，無機翻生硬文句，完成文化合規審核。
Gate 2: Design Ready
  └─ CIS 規範完整落實：山海青/晨曦金比例精確，黃金比例 Logo 驗算通過。
Gate 3: Build Ready
  └─ CI/CD Build 成功，無 ESLint/Stylelint 警告，靜態資產編譯壓縮無誤。
Gate 4: Integration Ready
  └─ 三大預售頁跳轉路由無縫銜接，API 端點與多語狀態切換無延遲。
Gate 5: Content & Legal Ready
  └─ Legal Entity 揭露合法，PDPA/GDPR/Cookie 條款經法務確認，無誇大醫療/政治宣傳。
Gate 6: Release Ready
  └─ Azure Static Web Apps 藍綠部署測試完成，自訂網域 SSL/TLS 正常，回滾腳本就緒。
Gate 7: Post-Release
  └─ 全球 8 大區域節點 CDN 驗收，DNS 解析延遲低於 150ms，無斷鏈。
```

### 5.4 部署架構與安全原則
* **嚴禁使用 GitHub Pages 進行商業交易**：
  * GitHub Pages 僅允許保留作為內部開發 Preview 或靜態文件展示。
  * 正式商用站點部署路徑：
    $$\text{GitHub Repository} \xrightarrow{\text{GitHub Actions CI/CD}} \text{Azure Static Web Apps} \xrightarrow{\text{Custom Domain (allview.today)}}$$
* **金流與敏感資訊邊界**：
  * 預售頁的付款、信用卡與下單金流不落地在靜態網站內，統一安全跳轉至符合 PCI-DSS 與台灣稅籍發票規範的正式金流服務商。
  * 任何涉及 FHE 或使用者私密金鑰之流程，均不進入雲端資料庫儲存，嚴守資料主權界限。


## v0.3 變更註記（2026-11-11，Asia/Taipei）

僅修正本次涉及之品牌顯示名稱、網域文字及與 t12u 直接衝突的法人關係段落；repo／org、技術代碼、URL、路徑、分支及 email local part 均未變更。品牌與網域確認不代表內容核准；本文件為草稿 v0.3，其他來源規格僅供參考，未驗證的功能、效能、時程及合規不得視為核准。

後續 CIS 全面採 PR 流程 [待確認]；本次起實際一律透過 PR，不直接推送 main。

### 人工審核清單

- 完整法定名稱、登記資訊、設立沿革、網域持有人與技術協作／託管契約仍以已確認錨點為限，其他 [待確認] 標註維持。
- 既有版權權利人與授權條款未由本次品牌修訂推定變更；請確認 README 的版權行及 LICENSE 第 189 行 `Copyright [yyyy] [name of copyright owner]` 範本尚未填寫之權利人與年份。
- 保留的技術 URL／徽章／代碼若含歷史文字，並非現行品牌或法人歸屬聲明；如需替換 URL 或改名須另行確認。
- 其餘效能、法遵、交付與產品主張未經核驗，均待人工審核，不因本次修字或 PR 合併視為核准。
