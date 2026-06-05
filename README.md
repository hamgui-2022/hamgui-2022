<h1 align="center">こんにちは、李在赫（イ・ジェヒョク）です 👋</h1>
<h3 align="center">iOS Developer  ·  新しい挑戦を恐れず、焦らず一歩ずつ</h3>

<p align="center">
  🇰🇷 韓国・嘉泉大学校 人工知能学科 在学中（2022年入学）<br/>
  💼 <b>ゲーム業界・IT業界の両方</b>で新卒就職を目指しています 🇯🇵
</p>

---

## 👨‍💻 About Me

- 📱 **iOS アプリ開発（SwiftUI / UIKit）を主軸** に、複数のチームプロジェクト・長期ハッカソンで開発経験を積んできました
- 🌱 新しい挑戦として **Unreal Engine 5（C++）でのゲーム開発** を独学中
  *（※ 学習期間は iOS（Swift）より相対的に短いですが、焦らず着実に取り組んでいます）*
- 🤝 **UMC (University MakeUs Challenge)** や大学のチーム開発で、設計から実装・レビューまで協業経験あり
- 🇯🇵 **日本語：JLPT N1 満点取得（ビジネスレベル）**
- ✍️ モットーは **「新しい挑戦を恐れず、焦らず一歩ずつ成長する」**

```swift
struct Developer {
    let name         = "Lee Jaehyeok (이재혁 / 李在赫)"
    let university   = "Gachon University, AI Major"
    let mainStack    = ["iOS", "SwiftUI", "UIKit", "Mobile UX"]
    let challenging  = ["Unreal Engine 5 + C++", "Android / Kotlin"]
    let japanese     = "JLPT N1 満点 (Business Level)"
    let motto        = "新しい挑戦を恐れず、焦らず一歩ずつ"
}
```

---

## 🛠️ Tech Stack

**Main — iOS**  
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2396F3?style=flat&logo=apple&logoColor=white)
![Moya](https://img.shields.io/badge/Moya-F05138?style=flat)
![SnapKit](https://img.shields.io/badge/SnapKit-000000?style=flat)
![Kingfisher](https://img.shields.io/badge/Kingfisher-FF6B6B?style=flat)
![FSCalendar](https://img.shields.io/badge/FSCalendar-4DB6AC?style=flat)

**Currently Learning — Game & Android**  
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_5.5-0E1128?style=flat&logo=unrealengine&logoColor=white)
![Blueprint](https://img.shields.io/badge/Blueprint-313131?style=flat)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)

**Tools & Collaboration**  
![Xcode](https://img.shields.io/badge/Xcode-007ACC?style=flat&logo=xcode&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat&logo=androidstudio&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

---

## 📌 Pinned Projects

### 📱 iOS Projects ─ メインフォーカス

#### ✈️ [InsighTravel_iOS](https://github.com/hamgui-2022/InsighTravel_iOS) — AI Travel Assistant
> **SwiftUI / async-await / FastAPI 連携**

チャット → プランニング → 予約 までを 1 つの体験にまとめた **AI 旅行アシスタント iOS アプリ**。iOS フロントエンドを 1 人で担当しました。

- **SwiftUI チャット UI を end-to-end で設計・実装**
- 旅行コンテンツ用の **カード型 UI システム** を構築（旅程・天気・ホテル・フライト・予約確認 など 8 種類）
- マルチセッション・チャット履歴サイドバー、`UserDefaults` による**セッション永続化**
- 予約フロー（選択 → 入力フォーム → レビュー → 確定 → 履歴）を end-to-end で実装
- FastAPI バックエンドとの **URLSession + async/await** 通信レイヤを設計
- アプリアイコン・スプラッシュ画面・マスコット透かしなど **ブランディング** も担当

> 📦 MVVM + Feature-based モジュラー設計で、ViewModel を Single Source of Truth として整理。

---

#### 💌 [Blism_iOS](https://github.com/UMC-Blism/Blism_iOS) — Letter App *(3人チーム / 長期ハッカソン)*
> **UIKit / SnapKit / Moya / Then / Kingfisher** — UMC 7期 長期ハッカソン B チーム

「届ける」をコンセプトにした **手紙アプリ**。iOS チーム 3 人で 4 ヶ月間開発しました。

- **担当：手紙作成画面 / 検索画面**
- UIKit + SnapKit による**コードベースのレイアウト構築**
- Moya で REST API 通信、Then による設定の簡潔化、Kingfisher で画像キャッシュ
- ブランチ戦略・コミット規約・PR レビューを徹底した**チーム開発フロー**を経験

---

#### 🌟 [RoutinA-iOS](https://github.com/Team-RoutinA/RoutinA-iOS) — Routine Habit App *(2人チーム)*
> **SwiftUI / Moya / FSCalendar** — 嘉泉大学校 モバイルプログラミング授業 4 班

ルーティン習慣形成のための iOS アプリ。iOS 2 人体制で開発しました。

- **担当：スプラッシュ画面 / ルーティン実行・結果ロギング機能 / 達成フィードバック画面**
- ルーティン実行画面の **タイマー進行ロジック** と、結果データのモデリング・永続化
- 達成度に応じた **フィードバック UI** を実装

---

#### 📓 [MOGAK_iOS](https://github.com/Team-MOGAK/MOGAK_iOS) — Self-Development App *(チーム)*
> **Swift / CocoaPods** — UMC 4期 夏休みプロジェクト

自己啓発のモチベーションを支える iOS アプリ。**iOS 開発入門期のチームプロジェクト** として参加。  
チームメンバーとして機能実装・UI 構築・API 連携を担当し、Git/GitHub を用いた共同開発の基本を身につけました。

---

### 🌱 New Challenges ─ 独学で挑戦中

#### 🎮 [UE5.5_DS1](https://github.com/hamgui-2022/UE5.5_DS1) — Soulslike Action Game *(個人プロジェクト)*
> **Unreal Engine 5.5 / C++ 97%**  
> *iOS と並行して、新しい挑戦として独学中（学習期間は Swift より相対的に短め）*

『Dark Souls』にインスパイアされた **ソウルライクアクションゲーム** を、Unreal Engine 5.5 で個人開発しているプロジェクトです。  
ゲーム開発・C++ ともに独学で取り組んでおり、「**実際に手を動かして作りながら理解する**」をテーマに、商用エンジンとゲームアーキテクチャに少しずつ慣れていくことを目的としています。

- **C++ ベースのキャラクター・戦闘システム** を実装（プレイヤーステート、ロックオン、攻撃モーション、ダメージ判定）
- **Blueprint と C++ のハイブリッド設計** で、ロジックは C++、調整しやすい部分は Blueprint に分離
- アニメーションブループリント、ステートマシンを用いた**モーション制御**

> 🌱 主力の iOS とは異なる新しい領域への挑戦。焦らず一歩ずつ、ゲーム開発の基礎を積み上げています。

---

#### 🎯 [GoalGiver_Front](https://github.com/UMC-GoalGiver/GoalGiver_Front) — Goal Sharing App *(Android)*
> **Kotlin / Java** — UMC Android プロジェクト

目標を共有するソーシャルアプリの **Android クライアント**。  
iOS で得た知見を活かしつつ、**新しいプラットフォームとしての Android** にチャレンジ。Kotlin + Java で画面実装と API 連携を担当しました。

---

## 🌱 Currently Working On

- 📱 `InsighTravel_iOS` 卒業制作を６月まで進行中
- 🎮 `UE5.5_DS1` の **敵 AI（Behavior Tree）** と戦闘システム拡張
- 📚 ゲームアーキテクチャ・最適化に関する読書
- 🇯🇵 業界研究（ゲーム会社・IT 企業）と職種研究


---

## 📫 Contact

- 📧 **Email**：ohjhlee14@gachon.ac.kr
- 💼 **LinkedIn**：（準備中）
- 📝 **Portfolio**：https://l-j-h.notion.site/?source=copy_link

<p align="center">
  <i>「新しい挑戦を恐れず、焦らず一歩ずつ」<br/>長く一つの場所で成長していける開発者を目指しています。</i>
</p>
