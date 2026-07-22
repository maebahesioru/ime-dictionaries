# インターネットミーム・サブカルチャー IME辞書コレクション

日本のインターネットミーム・サブカルチャー界隈の用語をまとめたIME辞書ファイル集です。

> 📥 **使い方**: 各 `.txt` ファイルをダウンロードして、IMEの「辞書ツール」からインポートしてください。  
> 🌟 一括で入れたい人は [`all_ime_dictionary.txt`](./all_ime_dictionary.txt) が便利です。

---

## 🖥️📱 プラットフォーム対応表

| プラットフォーム | Google日本語入力 / Mozc | Microsoft IME | 標準IME (iOS/macOS) |
|---|---|---|---|
| **Windows** | ✅ 完全対応 | ✅ 対応 | — |
| **Mac** | ✅ 対応 [`macos-compatible/`](./macos-compatible/) 参照 | — | ❌ 形式違い |
| **Linux** | ✅ 対応 (ibus/fcitx) | — | ❌ |
| **ChromeOS** | ✅ 完全対応（内蔵） | — | — |
| **Android** | ✅ Gboard / Mozc対応 | — | — |
| **iOS** | ❌ Gboard非対応 | — | ❌ 一括登録不可 |

### 🔧 その他のIME対応

| IME | 対応 | 備考 |
|---|---|---|
| **ATOK** | ✅ [`atok-utf16/`](./atok-utf16/) 参照 | UTF-16版を用意済み。文字コード以外は完全互換 |
| **Simeji** | ✅ インポート可 | 設定 → ユーザー辞書 → インポート |
| **Flick** | ✅ インポート可 | Gboard辞書のインポートに対応＝タブ区切り形式そのまま使用可 |
| **Copilot Keyboard** | ⚠️ 直接インポート不可 | MS-IME辞書からの引き継ぎのみ。テキストファイル直接読込には非対応 |
| **azooKey** | ❌ 非対応 | ユーザー辞書の一括インポート機能なし（iOS/Mac/Windows共通） |

> 💡 **iOSユーザーへ**: 標準IME・Gboardとも辞書の一括インポートに非対応です。ATOK for iOS（有料）のみ辞書インポートが可能です。  
> 💡 **Macユーザーへ**: 標準日本語入力の方は [`macos-compatible/`](./macos-compatible/) フォルダのカンマ区切り版を使ってください（ドラッグ&ドロップで追加辞書に読込可）。Google日本語入力（無料）または Mozc をお使いの方はルートのUTF-8版がそのまま使えます。ATOK for Mac をお使いの方は [`atok-utf16/`](./atok-utf16/) フォルダをご利用ください。  
> 💡 **ATOKユーザーへ**: UTF-16版を `atok-utf16/` フォルダに用意しています。ファイル名の先頭に `atok-utf16/` を付けてダウンロードしてください。  
> 💡 **ChromeOSユーザーへ**: ChromebookにはGoogle日本語入力が内蔵されています。Windows/Macと同じ手順でインポートできます。

---

## 📚 収録辞書一覧

| ファイル名 | 収録語数 | 内容 |
|---|---|---|
| `koushin_ime_dictionary.txt` | 526行 | 恒心教・ハセカラ関連語録（尊師/チンフェ/ハセカラファミリー等） |
| `tikan-reisyou_ime_dictionary.txt` | 1,072行 | 冷笑系・痴漢界隈語録（冷笑構文/冷笑戦隊/うおw等） |
| `hikakinmania-gaymasuo_ime_dictionary.txt` | 1,194行 | ヒカキンマニア用語（ヒカマニ語録/キャラ/構文等） |
| `hikamer_ime_dictionary.txt` | 1,840行 | ヒカマー界隈語録（ヒカマーズ/アルカイダー/作品名等） |
| `inmu_ime_dictionary.txt` | 1,072行 | 淫夢語録（野獣先輩/KMR/TNOK等） |
| `all_ime_dictionary.txt` | 5,704行 | 🌟 全辞書まとめ版（1ファイルで全5辞書） |

**合計: 5,704語**

---

## 📥 インポート方法

### Google 日本語入力 / Mozc (Windows / Linux / Chromebook)
1. タスクトレイのIMEアイコンを右クリック → **辞書ツール**
2. **管理** → **新規辞書にインポート**
3. ダウンロードした `.txt` ファイルを選択
4. 文字コードは **UTF-8** を選択

> 💡 Mozc は Google 日本語入力のオープンソース版なので、フォーマットもインポート手順も共通です。Linux (ibus-mozc / fcitx-mozc / emacs-mozc) でも同じ手順で使えます。

### Microsoft IME (Windows 10/11)
1. タスクトレイの「あ」/「A」アイコンを右クリック → **ユーザー辞書ツール**
2. **ツール** → **テキストファイルから登録**
3. ダウンロードした `.txt` ファイルを選択

### macOS (日本語入力)
1. システム環境設定 → **キーボード** → **ユーザー辞書**
2. ドラッグ&ドロップでファイルを追加（※要変換）

---

## 📋 辞書フォーマット

```
よみ<TAB>単語<TAB>品詞<TAB>コメント
```

例:
```
こうしん	恒心	名詞	基本用語
うお	うおw	感動詞	代表的冷笑語録
```

---

## ⚠️ 注意事項

- これらの辞書は**インターネットミーム・サブカルチャーの記録/研究**を目的としています
- 実在の人物・団体とは一切関係ありません
- 辞書に含まれる語句は各コミュニティ内で使用されるものです
- 追加・修正のPRは歓迎します

---

## 🔗 関連リンク

- [Google 日本語入力 辞書ツールの使い方](https://support.google.com/ime/answer/2791565)
- [Microsoft IME ユーザー辞書について](https://support.microsoft.com/ja-jp/windows/microsoft-ime)

---

## 📝 ライセンス

これらの辞書データは [CC0 1.0 (Public Domain)](https://creativecommons.org/publicdomain/zero/1.0/) で提供します。自由に改変・再配布してください。
