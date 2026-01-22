# Zbale Adjuster

VRChatアバター向けのボーン調整支援ツールです。  
Bone utility tool for VRChat avatars.  

[日本語](#日本語) | [English](#english)

---

## 日本語

### 概要
**Zbale Adjuster** は、VRChatアバターのボーン構造間で  
以下の要素を安全にコピーするための Editor 拡張ツールです。

- Transform（Position / Rotation / Scale）
- ModularAvatar ScaleAdjuster

---

### 主な機能

- シンプルモード / カスタムモード
- Transform のコピー（位置・回転・スケール）
- ModularAvatar ScaleAdjuster のコピー
- Hierarchy 右クリックから即実行（Execution）
- VRC Constraint 系コンポーネントは自動除外

---

### 動作環境

- Unity 2019.4 以上
- VRChat Creator Companion
- Modular Avatar

---

### インストール方法（VCC）

1. VRChat Creator Companion を起動
2. **Settings → Packages → Add Repository**
3. 以下のURLを追加  
https://github.com/zbelqcraft/ZbaleAdjuster
4. Packages タブから **Zbale Adjuster** をインストール

---

### 使い方（基本）

#### Execution版（おすすめ）
1. Hierarchy 上の任意のオブジェクトを右クリック
2. **ZbaleAdjuster → Execution**
3. ModularAvatar MergeArmature を自動検出して実行

#### Tool版
1. Unity メニューから  
   **Tools → ZbaleAdjuster**
2. コピー元とコピー先を指定
3. 必要な設定を選択して実行

---

### 注意事項

- VRCRotationConstraint / VRCConstraint 系はコピー対象外です
- 本ツールは Editor 専用です（Runtime では動作しません）

---

## English

### Overview
**Zbale Adjuster** is an Editor utility tool for VRChat avatars.  
It safely copies the following elements between bone hierarchies:

- Transform (Position / Rotation / Scale)
- ModularAvatar ScaleAdjuster

The tool is designed with simplicity and safety in mind.

---

### Features

- Simple mode / Custom mode
- Transform copy (Position, Rotation, Scale)
- ModularAvatar ScaleAdjuster copy
- Hierarchy right-click execution
- Automatically excludes VRC Constraint components

---

### Requirements

- Unity 2019.4 or later
- VRChat Creator Companion
- Modular Avatar

---

### Installation (VCC)

1. Open VRChat Creator Companion
2. Go to **Settings → Packages → Add Repository**
3. Add the following URL:  
https://github.com/zbelqcraft/ZbaleAdjuster
4. Install **Zbale Adjuster** from the Packages tab

---

### Usage

#### Tool Version
1. Open **Tools → ZbaleAdjuster**
2. Assign source and target Transforms
3. Configure settings and execute

#### Execution Version (Recommended)
1. Right-click an object in the Hierarchy
2. Select **ZbaleAdjuster → Execution**
3. The tool automatically finds MergeArmature and executes

---

### Notes

- VRCRotationConstraint and VRCConstraint components are excluded
- Editor-only tool (not included in runtime builds)

---

### License
MIT License

