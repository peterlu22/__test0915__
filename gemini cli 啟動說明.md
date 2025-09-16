# Gemini CLI 啟動說明

本文檔介紹了啟動 Gemini CLI 的幾種常用方法。

## 1. 基本啟動

這是最簡單的啟動方式，CLI 將在前台運行。

```bash
gemini-cli start
```

## 2. 背景啟動

如果您希望 CLI 在背景運行，可以使用 `&` 符號。

```bash
gemini-cli start &
```

## 3. 使用特定的設定檔啟動

您可以指定一個設定檔來啟動 CLI。

```bash
gemini-cli start --config /path/to/your/config.yaml
```

## 4. 啟用除錯模式

若要以除錯模式啟動，請使用 `--debug` 旗標。

```bash
gemini-cli start --debug
```
