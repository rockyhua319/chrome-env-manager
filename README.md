# Chrome 環境管理器 · 下載

用圖形介面管理多個互相隔離的 Chrome 環境，一鍵開啟；可同時登入同一個網站的多個帳號，代理可選。

## 下載

**最新版：[Releases 頁面](https://github.com/rockyhua319/chrome-env-manager/releases/latest)**

| 版本 | 檔案 | 說明 |
| --- | --- | --- |
| 0.1.3 | [ChromeEnvManager-0.1.3-macos.zip](https://github.com/rockyhua319/chrome-env-manager/raw/main/ChromeEnvManager-0.1.3-macos.zip) | macOS 13 以上，Intel 與 Apple Silicon 通用 |
| 0.1.2 | [ChromeEnvManager-0.1.2-macos.zip](https://github.com/rockyhua319/chrome-env-manager/raw/main/ChromeEnvManager-0.1.2-macos.zip) | macOS 13 以上，Intel 與 Apple Silicon 通用 |
| 0.1.1 | [ChromeEnvManager-0.1.1-macos.zip](https://github.com/rockyhua319/chrome-env-manager/raw/main/ChromeEnvManager-0.1.1-macos.zip) | macOS 13 以上，Intel 與 Apple Silicon 通用 |
| 0.1.0 | [ChromeEnvManager-0.1.0-macos.zip](https://github.com/rockyhua319/chrome-env-manager/raw/main/ChromeEnvManager-0.1.0-macos.zip) | macOS 13 以上，Intel 與 Apple Silicon 通用 |

需要先安裝 [Google Chrome](https://www.google.com/chrome/)。

## 安裝

1. 下載 zip，雙擊解壓，得到「Chrome 環境管理器」。
2. 把它拖進「應用程式」資料夾。
3. 第一次打開時 macOS 會擋一下（這個應用還沒有 Apple 的公證），照下面做一次就好，之後都正常：

   **macOS 15（Sequoia）或更新**
   - 雙擊打開，看到「無法打開」的提示後按「完成」。
   - 打開「系統設定」→「隱私權與安全性」，往下捲到「安全性」，會看到「已阻擋 Chrome 環境管理器」，按旁邊的「仍要打開」，再按一次「打開」。

   **macOS 13 / 14**
   - 在「應用程式」裡對「Chrome 環境管理器」按右鍵（或按住 Control 點一下）→「打開」→ 再按「打開」。

4. 之後從 Launchpad、Spotlight 或「應用程式」資料夾打開即可。

## 第一次使用

1. 應用會自動找到 Chrome。
2. 輸入要建立幾個環境，按「建立」。
3. 每張卡片點一下就會開出一個獨立的 Chrome 視窗，各自的登入狀態互不相通。
4. 需要代理時，到「代理」頁把代理放進代理庫（貼上或連接代理平台），再分配給環境；不用代理也可以直接使用。

資料存放位置：`~/Library/Application Support/ChromeEnvManager/`
