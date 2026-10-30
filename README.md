## 濱田 怜央 / Reo Hamada

![湘南工科大学](https://img.shields.io/badge/湘南工科大学-情報工学専攻_2年-0A4D8C?style=flat-square)
![酒造研究室](https://img.shields.io/badge/酒造研究室-AI_%2F_IoT-2E7D32?style=flat-square)
[![Mail](https://img.shields.io/badge/Mail-25b2067%40sit.shonan--it.ac.jp-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:25b2067@sit.shonan-it.ac.jp)

> 湘南工科大学情報学部情報学科2年在学中．ロボティクス，組込みシステム，画像認識，対話システムなどの研究開発に取り組む．2026年に開催された対話システムライブコンペティション8（DSLC8）では，チームShonanGreenAppleの主たる開発エンジニアとしてシステムの設計・実装を担当．  
> Second-year student in the Department of Information Science, Shonan Institute of Technology, working on research and development in robotics, embedded systems, computer vision, and dialogue systems. At the Dialogue System Live Competition 8 (DSLC8) in 2026, served as the lead development engineer for team ShonanGreenApple, responsible for system design and implementation.

### 関心のある分野 / Interests

- ロボットとの共生社会をめざした AI / IoT 技術（研究室テーマ）  
  AI / IoT for human-robot coexistence
- 音声対話システム・ロボットとの対話  
  Spoken dialogue systems and human-robot interaction
- 画像認識（物体検出・追跡・CG による合成データ）  
  Computer vision: object detection, tracking, and synthetic training data from CG
- 生成 AI・ローカル LLM を使ったツールづくり  
  Building tools with generative AI and local LLMs


### 活動 / Activities

- 対話システムライブコンペティション8（DSLC8）に、チーム ShonanGreenApple の主たる開発エンジニアとして参加  
  Participated in Dialogue System Live Competition 8 (DSLC8) as the lead development engineer for team ShonanGreenApple
- ビジョン技術の実利用ワークショップ（ViEW2026）参加  
  Participated in Vision Engineering Workshop (ViEW2026)

### 取り組み中 / Current Work

研究・コンペのため、リポジトリは非公開です。  
These repositories are private while the research and competitions are in progress.

- **ABC2027 Challenge — UWB レーダーによる転倒検出**  
  カメラを使わない UWB レーダーの信号から、転倒した区間を見つける。転倒する前にその日の危険度を出す試作システム（ローカル LLM が記録をまとめる）も作っている  
  Fall detection from camera-free UWB radar signals, plus a prototype that estimates the day's fall risk before a fall happens, using a local LLM
- **ABC2027 TrackID3x3 Challenge — 3x3 バスケットボールの選手追跡と識別**  
  試合動画から、選手ごとのコート上の位置・チーム・背番号を推定する（YOLO で検出 → コート座標へ変換 → 追跡 → 背番号の分類と OCR → 整数計画法で ID を割り当て）  
  Estimating each player's court position, team, and jersey number from match video (YOLO detection, court projection, tracking, jersey classification and OCR, and ID assignment with integer programming)
- **ViEW — CG によるボウフラ検出用の合成データセット**  
  Blender で、ハマダラカの幼虫（ボウフラ）が入った水面の画像と正解枠を自動で作る（1,000 枚・10,000 匹）。YOLO と Google Cloud AutoML の形式で出力  
  Generating synthetic images of *Anopheles* larvae in water with Blender, with automatic bounding boxes (1,000 images, 10,000 larvae) in YOLO and Google Cloud AutoML formats

### 作ったもの / Projects

#### AI ツール / AI Tools

<table>
<tr>
<td width="50%" valign="top">

**[ai-page-translator](https://github.com/hamadareo/ai-page-translator)**  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Chrome Extension](https://img.shields.io/badge/Chrome_Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-6E56CF?style=flat-square)

Web ページ全体を生成 AI で日本語に翻訳する Chrome 拡張。OpenAI / Anthropic / Gemini とローカル LLM（LM Studio、自動起動つき）に対応し、レイアウトを崩さずに置き換える。クリックしたリンク先も自動で翻訳  
A Chrome extension that translates whole web pages with generative AI (OpenAI / Anthropic / Gemini or a local LLM via LM Studio with auto-start), keeping the page layout and following clicked links

</td>
<td width="50%" valign="top">

**[AI-browser](https://github.com/hamadareo/AI-browser)**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)
![Local LLM](https://img.shields.io/badge/Local_LLM-6E56CF?style=flat-square)

ローカル LLM（LM Studio）でブラウザを自動操作する AI エージェント。Python（Playwright）版と Chrome 拡張版  
A browser automation agent powered by a local LLM, available as a Python (Playwright) app and a Chrome extension

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[codedeck](https://github.com/hamadareo/codedeck)**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![macOS / Windows](https://img.shields.io/badge/macOS_%2F_Windows-555555?style=flat-square)

Claude Code の複数アカウント・複数セッションを1つの画面で管理するデスクトップアプリ（macOS / Windows）。Anthropic の公式製品ではない、個人開発の非公式ツール  
A desktop app for running Claude Code sessions across multiple accounts in one window (macOS / Windows). An unofficial tool, not affiliated with Anthropic

</td>
<td width="50%" valign="top">

**[license-plate-eraser](https://github.com/hamadareo/license-plate-eraser)**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=ultralytics&logoColor=white)
![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white)

写真・動画のナンバープレートを AI（YOLO）で自動検出して、モザイク・白塗り・AI 修復で消すデスクトップアプリ  
A desktop app that detects license plates in photos and videos with YOLO and hides them with mosaic, fill, or AI inpainting

</td>
</tr>
</table>

#### ロボット・ドローン / Robots & Drones

<table>
<tr>
<td width="50%" valign="top">

**[razipai-rc-car](https://github.com/hamadareo/razipai-rc-car)**  
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![TWELITE](https://img.shields.io/badge/TWELITE-555555?style=flat-square)

ブラウザから操縦できる大型 RC カー。Raspberry Pi + Arduino + TWELITE で、カメラによるライントレースにも対応  
A browser-controlled RC car using Raspberry Pi, Arduino, and TWELITE, with camera-based line tracing

</td>
<td width="50%" valign="top">

**[tello-line-tracer](https://github.com/hamadareo/tello-line-tracer)**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![DJI Tello](https://img.shields.io/badge/DJI_Tello-000000?style=flat-square&logo=dji&logoColor=white)

DJI Tello のカメラで床のラインを追いかけて自動飛行。コース学習とブラウザのダッシュボードつき  
Autonomous line-following flight for the DJI Tello, with course learning and a web dashboard

</td>
</tr>
</table>

#### 映像・音 / Visual & Audio

<table>
<tr>
<td width="50%" valign="top">

**[vfd-spectrum](https://github.com/hamadareo/vfd-spectrum)**  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Web Audio](https://img.shields.io/badge/Web_Audio-FF6F00?style=flat-square)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

90〜2000年代のカーオーディオ風、蛍光表示管（VFD）スペクトラムアナライザー。ブラウザ（Canvas + Web Audio）と Mac アプリで動作  
A retro car-audio style VFD spectrum analyzer for the browser and macOS

</td>
<td width="50%" valign="top"></td>
</tr>
</table>

### 使っている技術 / Tech

- **言語 / Languages**  
  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
  ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
  ![CSS](https://img.shields.io/badge/CSS-663399?style=flat-square&logo=css&logoColor=white)
  ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
  ![C++ (Arduino)](https://img.shields.io/badge/C%2B%2B_(Arduino)-00599C?style=flat-square&logo=cplusplus&logoColor=white)
- **AI・画像処理 / AI & Vision**  
  ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
  ![YOLO (Ultralytics)](https://img.shields.io/badge/YOLO_(Ultralytics)-111F68?style=flat-square&logo=ultralytics&logoColor=white)
  ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
  ![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
  ![ローカル LLM (LM Studio)](https://img.shields.io/badge/ローカル_LLM-LM_Studio-6E56CF?style=flat-square)
- **Web・アプリ / Web & Apps**  
  ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
  ![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=flat-square&logo=qt&logoColor=white)
  ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
  ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)
  ![Chrome 拡張](https://img.shields.io/badge/Chrome_拡張-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
  ![Web Audio API](https://img.shields.io/badge/Web_Audio_API-FF6F00?style=flat-square)
  ![Canvas](https://img.shields.io/badge/Canvas-555555?style=flat-square)
- **ハードウェア / Hardware**  
  ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
  ![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
  ![TWELITE](https://img.shields.io/badge/TWELITE-555555?style=flat-square)
  ![DJI Tello](https://img.shields.io/badge/DJI_Tello-000000?style=flat-square&logo=dji&logoColor=white)

### 連絡先 / Contact

- Mail: 25b2067@sit.shonan-it.ac.jp
