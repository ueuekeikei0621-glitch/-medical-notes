# ER 呼吸困難：オーバートリアージ検査戦略（完全版）

> **方針**：救急外来の急性呼吸困難は **見逃し = 死** につながる killer disease を含むため、
> **感度優先（rule-out 志向）** で並列に検査を出す。トリアージ段階では
> 「陰性を示す」ことを目的に検査バッテリーを走らせ、pretest probability を高めた症例には
> 追加画像（CTPA、造影 CT、心エコー）を組み合わせる。
> 本ノートは **① 初動 → ② 網羅的鑑別 → ③ 検査バッテリー → ④ スコア → ⑤ 疾患別ワークアップ →
> ⑥ 治療的介入 → ⑦ Disposition → ⑧ Pitfall** の順で構成。

- 対象：成人 ER 受診の急性呼吸困難（<数日）
- 想定読者：ER・総合内科・研修医
- 更新日：2026-09-06

---

## 目次

1. 概念と定義（Type I/II 呼吸不全、hypoxia の 5 機序）
2. First 5 minutes：ABCDE と即決事項
3. 網羅的鑑別（killer + common）
4. 病歴聴取テンプレ（SAMPLE + OPQRST + Red flag）
5. 身体所見の鍵（disease-specific findings）
6. 検査バッテリー（並列オーダー）
7. ABG 完全解釈（A-aDO₂、AG、compensation）
8. バイオマーカー（hs-cTn / BNP / NT-proBNP / D-dimer / PCT / Lactate）
9. リスクスコア全項目
10. POCUS 詳細（BLUE / FoCUS / RUSH / DVT）
11. 画像戦略（CXR/CTPA/造影 CT/心エコー）
12. 疾患別ワークアップ
    - 12-1 肺塞栓
    - 12-2 ACS
    - 12-3 急性心不全
    - 12-4 肺炎・敗血症
    - 12-5 COPD 増悪
    - 12-6 喘息
    - 12-7 気胸
    - 12-8 大動脈解離
    - 12-9 心タンポナーデ
    - 12-10 アナフィラキシー
    - 12-11 上気道閉塞
    - 12-12 代謝性アシドーシス（DKA、乳酸、中毒）
    - 12-13 神経筋（GBS、MG クリーゼ）
13. 治療介入（O₂、HFNC、NPPV、挿管、薬剤投与量）
14. 特殊集団（妊婦、高齢者、透析、免疫不全、精神科既往）
15. Disposition 判断
16. Pitfall 集
17. Japan-specific（保険適応・診療報酬）
18. 参考文献

---

## 1. 概念と定義

### 1-1. 呼吸不全の分類
- **Type I（低酸素性）**：PaO₂ <60 mmHg、PaCO₂ 正常 or 低下
  - 病態：V/Q ミスマッチ、シャント、拡散障害、低吸入 O₂
  - 例：肺炎、PE、ARDS、肺水腫、間質性肺炎
- **Type II（高炭酸ガス性）**：PaCO₂ >45 mmHg（±PaO₂ 低下）
  - 病態：肺胞低換気
  - 例：COPD 増悪、重症喘息 late phase、神経筋、CNS 抑制、胸郭疾患

### 1-2. 低酸素血症の 5 機序
| 機序 | A-aDO₂ | O₂ 反応 | 例 |
|---|---|---|---|
| 低吸入 O₂ | 正常 | 良 | 高地、火災 |
| 低換気 | 正常 | 良 | 麻薬中毒、神経筋 |
| V/Q ミスマッチ | 開大 | 良 | COPD、喘息、肺炎、PE |
| 拡散障害 | 開大 | 良 | 間質性肺炎、肺水腫 |
| 右左シャント | 開大 | **不良** | ARDS、無気肺、心内シャント |

A-aDO₂ = (713 × FiO₂ − PaCO₂/0.8) − PaO₂
正常上限 ≒ (年齢/4) + 4 （room air）

### 1-3. 「呼吸困難」の定量
- **修正 Borg スケール（0–10）**、**mMRC（0–4）**、**NRS 呼吸困難**
- 起座呼吸／夜間発作性呼吸困難／労作時呼吸困難 → 心不全示唆
- 発症時間軸（急性 <数時間、亜急性 <数日、慢性 >数週）で鑑別を絞る

---

## 2. First 5 minutes：ABCDE と即決事項

### 2-1. 即断ルール（"Sick or Not Sick"）
以下に **1 つでも該当** すれば即 resuscitation room：
- 会話不能／単語しか話せない
- 起座呼吸／三尖鎖骨窩陥没／努力呼吸（Retractions）
- チアノーゼ、意識障害（GCS ≤14）
- SpO₂ <90%（room air）
- RR ≥30 / min or ≤8 / min
- 収縮期血圧 <90 mmHg or lactate >4
- Stridor、silent chest

### 2-2. モニタと初期処置（並列）
- **心電図モニタ、SpO₂、NIBP、体温、RR** を連続表示
- **末梢静脈路 2 本（18G 以上）** + 採血採取
- **酸素**：SpO₂ 94–98% を目標（COPD 疑いは 88–92%）※BTS 2017
  - 経鼻カニュラ 1–6 L/min → simple mask 6–10 L/min → reservoir mask 10–15 L/min → HFNC → NPPV → 挿管
- **12 誘導 ECG**（10 分以内、必ず記録）
- **CXR portable**（10 分以内目標）
- **ABG**（Lactate、COHb、MetHb、iCa、Glu 同時）
- **POCUS（BLUE + FoCUS + IVC + DVT）** を主治医が自ら
- **エコー室ではなくベッドサイド**で実施

### 2-3. 両上肢血圧・下肢腫脹の確認
- **上肢差 >20 mmHg** → 大動脈解離
- **片側下腿腫脹** → DVT / PE
- **JVD + Kussmaul 徴候** → タンポナーデ、右室梗塞、拘束性

---

## 3. 網羅的鑑別（Killer + Common）

### 3-1. Killer（見逃しゼロ）
| 分類 | 疾患 | 見逃しのサイン |
|---|---|---|
| 気道 | 上気道閉塞（Angioedema、喉頭蓋炎、Ludwig、異物） | Stridor、drooling、tripod position |
| 気道 | Tracheobronchial disruption | 皮下気腫、縦隔気腫 |
| 呼吸 | 緊張性気胸 | 患側呼吸音消失＋気管偏位＋JVD |
| 呼吸 | 血胸（大量） | 患側 dull＋ショック |
| 呼吸 | 重症肺炎（sepsis） | qSOFA≥2、Lac >2 |
| 呼吸 | ARDS | 低酸素＋両側浸潤影＋非心原性 |
| 呼吸 | Severe asthma / silent chest | 話せない、silent chest、PEF <33% |
| 循環 | AMI（特に inferior + RV） | 冷汗、下壁 ST 上昇＋V4R |
| 循環 | 急性心不全（心原性肺水腫） | 起座呼吸、pink frothy sputum |
| 循環 | 心タンポナーデ | Beck 三徴、pulsus paradoxus >10 mmHg |
| 循環 | 大動脈解離 | 引き裂き痛、上肢血圧差、意識障害 |
| 循環 | 大 PE（massive/submassive） | 突然発症、失神、RV strain |
| 代謝 | DKA / HHS | Kussmaul 呼吸、高血糖、ケトン |
| 代謝 | 敗血症性ショック | 発熱＋qSOFA≥2＋Lac >2 |
| 代謝 | CO / シアン / MetHb 中毒 | 火災現場、皮膚 cherry red、pulse ox 正常でも SaO₂ 低下 |
| 代謝 | サリチル酸中毒 | 頻呼吸＋高体温＋耳鳴＋AG 開大 |
| 神経筋 | GBS、MG クリーゼ、頚髄損傷 | %VC <15 mL/kg、NIF -20 未満 |
| 血液 | 重症貧血、MetHb | Hb <7、SaO₂-SpO₂ gap |
| その他 | アナフィラキシー | 皮疹、血圧低下、喘鳴 |
| その他 | 頭蓋内病変（脳幹梗塞、SAH） | 神経症状＋呼吸パターン異常 |

### 3-2. Common（頻度で鑑別）
- 肺炎（CAP / NHCAP / HAP）
- COPD 増悪、喘息発作
- 心不全増悪
- 冠攣縮／狭心症
- 過換気症候群（除外診断）
- 誤嚥性肺炎
- 貧血、脱水
- 胸水（心不全、悪性、感染）
- 気管支炎、上気道炎
- 精神性（不安、パニック）

---

## 4. 病歴聴取テンプレ

### 4-1. OPQRST + 呼吸困難特化
- **Onset**：突然（PE、気胸、AMI）／数時間（AHF、CAP）／数日（COPD、喘息）
- **Provocation**：労作、臥位（起座）、寒冷、粉塵、感染前駆
- **Quality**：息が吸えない／吐けない／胸の圧迫感
- **Radiation**：胸背部痛（解離、AMI）、肩痛（横隔膜刺激）
- **Severity**：Borg / mMRC
- **Timing**：夜間発作、季節性、労作時

### 4-2. SAMPLE + 追加
- **S**：発熱、咳、痰、血痰、胸痛、動悸、失神、下肢腫脹、浮腫、体重増加
- **A**：アレルギー、Angioedema 既往、ACE-I 内服
- **M**：抗凝固薬、β-blocker、ACE-I/ARB、利尿薬、吸入薬（頻回 SABA 使用）、免疫抑制剤、抗癌剤、避妊薬、ホルモン療法、違法薬物（コカイン、覚醒剤）
- **P**：心不全、COPD、喘息、癌、DVT/PE、透析、SAS、精神疾患、妊娠
- **L**：直近の食事（DKA での吐き気）
- **E**：転倒、外傷、火災、閉鎖空間、長時間フライト、術後、寝たきり、旅行歴（COVID、結核、真菌）

### 4-3. Red flag
- **突然発症**（<数秒〜数分）→ PE、気胸、AMI
- **胸痛合併**：ACS、PE、解離、気胸、心膜炎、食道破裂
- **失神・意識障害合併**：大 PE、AMI、AAD、AS、不整脈
- **抗凝固薬内服 + 呼吸困難**：血胸、心タンポナーデ
- **癌既往**：PE、悪性胸水、癌性リンパ管症
- **妊娠 or 産褥**：PE、羊水塞栓、周産期心筋症

---

## 5. 身体所見の鍵

### 5-1. 全身
- 皮膚：チアノーゼ（中枢/末梢）、皮疹（アナフィラキシー、蕁麻疹）、cherry red（CO）、灰紫色（MetHb）
- 姿勢：起座呼吸、tripod position、silent chest（危険サイン）
- 発汗、末梢冷感（低灌流）

### 5-2. 呼吸系
- **視診**：胸郭運動左右差（気胸、無気肺）、努力呼吸、奇異呼吸、鎖骨窩・肋間陥没
- **触診**：皮下気腫、声音振盪（実質病変で亢進、胸水で減弱）
- **打診**：hyperresonance（気胸）、dullness（胸水、無気肺、実質炎）
- **聴診**：
  - Wheeze：喘息、COPD、cardiac asthma、上気道閉塞（monophonic）
  - Stridor：吸気性 → 声門・声門上、呼気性 → 声門下
  - Coarse crackles：肺水腫（両側下肺野〜）、肺炎（限局）
  - Fine crackles（velcro）：間質性肺炎
  - Pleural friction rub：胸膜炎
  - Silent chest：重症喘息、緊張性気胸

### 5-3. 循環系
- 頸静脈怒張（JVD）：右心不全、タンポナーデ、緊張性気胸
- Kussmaul 徴候：吸気で JVD ↑ → 拘束性、タンポナーデ、右室梗塞
- III 音：心不全（LV dysfunction）
- IV 音：心筋虚血、HCM
- 心膜摩擦音：心膜炎
- 拡張早期 clicks、収縮期雑音：AS、MR
- Pulsus paradoxus >10 mmHg：タンポナーデ、重症喘息、COPD

### 5-4. その他
- 下腿浮腫（両側 → 心不全、片側 → DVT）
- 腹部膨満（腹水、gastric distention）
- 神経所見：構音障害、瞳孔、四肢筋力（GBS 上行性、MG 眼瞼下垂）

---

## 6. 検査バッテリー（並列オーダー）

### 6-1. Bedside（0–10 分）
```
□ 12 誘導 ECG
□ ABG（Lactate, COHb, MetHb, iCa, Glu, K, Hb 同時）
□ CXR portable（立位 or 座位）
□ POCUS: BLUE + FoCUS + IVC + 両下肢 compression US
□ ベッドサイド血糖
□ SARS-CoV-2 / インフル / RSV 抗原 or PCR
□ ケトン（尿・血中β-OH）
□ (妊娠可能女性) β-HCG
```

### 6-2. 採血（0–30 分）
```
[血算・血液像]
□ CBC + differential
□ 網赤血球、末梢血塗抹（貧血・溶血・DIC 疑い時）

[生化学]
□ Na, K, Cl, HCO3, BUN, Cre, eGFR
□ Ca, Mg, P, iCa
□ Glu, HbA1c
□ AST, ALT, ALP, γGTP, T-Bil, D-Bil, LDH
□ CK, CK-MB
□ Alb, TP
□ アンモニア（意識障害）

[炎症・感染]
□ CRP
□ Procalcitonin（細菌性 vs ウイルス性、敗血症）
□ 血液培養 2 セット（発熱、qSOFA≥2、Lac >2）
□ 尿定性・沈渣、尿中肺炎球菌抗原、尿中レジオネラ抗原（血清型 1）
□ 喀痰グラム染色・培養
□ β-D グルカン、アスペルギルス抗原（免疫不全）
□ HIV スクリーニング（PCP 疑い）
□ QFT / T-SPOT（結核疑い、緊急性低）

[心筋・心不全]
□ hs-Troponin（0 h → 1 h or 3 h 再検、ESC 0/1h）
□ NT-proBNP or BNP
□ H-FABP（早期 AMI、施設による）

[凝固・PE]
□ PT-INR, APTT, Fibrinogen
□ D-dimer（年齢調整カットオフ）
□ アンチトロンビン、FDP（DIC 疑い）

[内分泌・その他]
□ TSH, FT4（頻脈、AF、原因不明の心不全）
□ Cortisol（副腎不全疑い）
□ 血清浸透圧、尿浸透圧、尿電解質（電解質異常時）
□ アルコール、薬物血中濃度（サリチル酸、アセトアミノフェン、テオフィリン、ジゴキシン、リチウム）
```

### 6-3. 画像
```
□ CXR portable（初診時）
□ CT 単純胸部（気胸、間質性、無気肺の詳細）
□ CTPA（PE 疑い、Wells/PERC/YEARS で除外できず）
□ 造影 CT 胸腹（大動脈解離、AAA、腸間膜虚血）
□ 頭部 CT（意識障害、抗凝固内服、解離疑い）
□ 頚部 CT（上気道閉塞、深頚部感染）
□ 心エコー（正式）：POCUS 異常、BNP 高値、原因不明
□ 腹部エコー / CT（右季肋部痛、横隔膜下病変）
```

---

## 7. ABG 完全解釈

### 7-1. Step
1. **pH**：<7.35 acidemia、>7.45 alkalemia
2. **PaCO₂**：>45 呼吸性 acidosis 寄与、<35 呼吸性 alkalosis 寄与
3. **HCO₃⁻**：<22 代謝性 acidosis 寄与、>26 代謝性 alkalosis 寄与
4. **AG** = Na − (Cl + HCO₃) 　正常 12±2（Alb で補正：AG補正 = AG + 2.5×(4−Alb)）
5. **代償**（Winters, etc.）
   - 代謝性 acidosis：PaCO₂ = 1.5 × HCO₃ + 8 ± 2
   - 代謝性 alkalosis：PaCO₂ = 0.7 × HCO₃ + 21 ± 2
   - 急性 呼吸性 acidosis：ΔpH = −0.008 × ΔPaCO₂
   - 慢性 呼吸性 acidosis：ΔpH = −0.003 × ΔPaCO₂
6. **Δ/Δ 比**（AG 開大代謝性 acidosis）：ΔAG / ΔHCO₃
   - <1：AG 開大 + 非開大の混合
   - 1〜2：pure AG 開大
   - >2：AG 開大 + 代謝性 alkalosis or 慢性呼吸性 acidosis

### 7-2. AG 開大代謝性 acidosis（MUDPILES / GOLDMARK）
- **GOLDMARK**（現代版）：**G**lycols (エチレン、プロピレン)、**O**xoproline (アセトアミノフェン過量)、**L**-lactate、**D**-lactate、**M**ethanol、**A**spirin、**R**enal failure、**K**etoacidosis (DKA, AKA)

### 7-3. A-aDO₂ 開大の意義
- 開大なし → 低換気 or 低吸入 O₂
- 開大あり → V/Q、拡散、シャント
- **PE の 15–25% は A-aDO₂ 正常**（若年で顕著）

### 7-4. Lactate
- >2 mmol/L：組織低灌流示唆（敗血症、心原性ショック、腸管虚血、CO/シアン、痙攣後、メトホルミン、β2 刺激大量）
- >4：J-SSCG で敗血症性ショックの qualifying value
- **type A（低灌流）vs type B（薬物・肝不全・悪性腫瘍）** を区別

### 7-5. CO / MetHb
- **CO-Hb >3%（非喫煙）、>10%（喫煙）** → 中毒
- **MetHb >1.5%** → 症状発現、>30% で危険
- **Pulse ox は SpO₂ 偽正常** に注意（cooximeter で SaO₂ 測定）

---

## 8. バイオマーカー詳細

### 8-1. 高感度トロポニン（hs-cTn）
- **ESC 0/1h アルゴリズム**（NSTE-ACS Guidelines 2020）
  - **Rule-out**：0 h <A（超低値）or (0 h <B かつ Δ1h <C)
  - **Rule-in**：0 h ≥D or Δ1h ≥E
  - **Observe**：それ以外 → 3 h 再検＋心エコー

| 試薬 | A (ng/L) | B (ng/L) | C | D (ng/L) | E |
|---|---|---|---|---|---|
| Elecsys hs-cTnT (Roche) | <5 | <12 | <3 | ≥52 | ≥5 |
| Architect hs-cTnI (Abbott) | <4 | <5 | <2 | ≥64 | ≥6 |
| Dimension hs-cTnI (Siemens) | <3 | <6 | <3 | ≥120 | ≥12 |

- **偽陽性**：CKD、AF、心不全、心筋炎、PE、脳梗塞、敗血症、外傷
- 常に **臨床像＋ECG＋動態変化** で総合判断

### 8-2. BNP / NT-proBNP
- **BNP <100 pg/mL** → 急性心不全 rule-out（NPV 高い）
- **BNP >400 pg/mL** → 心不全示唆
- **NT-proBNP 年齢別カットオフ**（rule-in）
  - <50 歳：>450
  - 50–75 歳：>900
  - >75 歳：>1800
  - **共通 rule-out：<300 pg/mL**
- **偽高値**：AF、高齢、腎不全、敗血症、PE、貧血
- **偽低値**：肥満、心膜炎、僧帽弁狭窄、閃光性肺水腫（超急性）

### 8-3. D-dimer
- 単位に注意（FEU vs DDU）
- 従来カットオフ：500 ng/mL FEU
- **年齢調整**（50 歳超）：年齢 × 10 ng/mL FEU
- **YEARS 併用**：YEARS 項目 0 個 → <1000、YEARS ≥1 → <500 で除外
- **妊娠**：CT-PE Pregnancy study では YEARS + trimester 別 D-dimer 使用可（NEJM 2019;380:1139）

### 8-4. Procalcitonin（PCT）
- <0.25 ng/mL：細菌感染の可能性低
- 0.25–0.5：グレー
- >0.5：細菌感染示唆、>2 で敗血症示唆
- **抗菌薬中止基準**：PCT が peak から 80% 低下 or <0.25（ProACT/SAPS）
- **ウイルス肺炎、COVID-19 では低値でも細菌合併あり** → 臨床像優先

### 8-5. Lactate
- 敗血症バンドル（Surviving Sepsis）：1 時間以内に測定、>2 で再検
- クリアランス >10%/2h が予後良好因子

### 8-6. その他
- **Copeptin**：AMI 早期除外の補助（+ hs-cTn）
- **MR-proADM**：肺炎重症度、心不全予後
- **H-FABP**：早期 AMI（発症 3 時間以内）

---

## 9. リスクスコア全項目

### 9-1. Wells score for PE
| 項目 | 点 |
|---|---|
| 臨床的 DVT 徴候 | 3 |
| 他の診断が PE より **可能性低い** | 3 |
| HR >100 | 1.5 |
| 直近 4 週の術後・免動 | 1.5 |
| 過去の DVT/PE | 1.5 |
| 血痰 | 1 |
| 悪性腫瘍（現・6 か月以内・緩和） | 1 |

- **2 段階**：≤4 unlikely（D-dimer で除外可）、>4 likely（CTPA）
- **3 段階**：<2 low、2–6 moderate、>6 high

### 9-2. Geneva Revised score
| 項目 | 点 |
|---|---|
| 年齢 >65 | 1 |
| DVT/PE 既往 | 3 |
| 1 か月以内の手術・骨折 | 2 |
| 活動性癌 | 2 |
| 片側下肢痛 | 3 |
| 血痰 | 2 |
| HR 75–94 | 3 |
| HR ≥95 | 5 |
| 下肢圧痛＋片側浮腫 | 4 |

- Low <4、Intermediate 4–10、High ≥11

### 9-3. PERC rule（**8 項目全て陰性 + low pretest** で PE 除外）
1. 年齢 <50
2. HR <100
3. SpO₂ ≥95%（room air）
4. 血痰なし
5. エストロゲン使用なし
6. DVT/PE 既往なし
7. 片側下肢腫脹なし
8. 手術・外傷（4 週以内）なし

### 9-4. YEARS algorithm
- 3 項目：DVT 徴候／血痰／PE が最も疑わしい
- 全て陰性 → D-dimer <1000 で除外
- 1 つでも陽性 → D-dimer <500 で除外
- それ以外 → CTPA

### 9-5. HEART score for ACS
| 項目 | 0 | 1 | 2 |
|---|---|---|---|
| History | Slightly suspicious | Moderately | Highly |
| ECG | 正常 | 非特異的 STT | 有意 ST 偏位 |
| Age | <45 | 45–64 | ≥65 |
| Risk factors | 0 | 1–2 | ≥3 or 動脈硬化性疾患 |
| Troponin | ≤正常上限 | 1–3× | >3× |

- 0–3：低リスク（30 日 MACE <2%）→ 帰宅可
- 4–6：中等度 → 入院精査
- 7–10：高リスク → 早期侵襲的評価

### 9-6. GRACE score for NSTE-ACS（院内・6 か月死亡）
- 年齢、HR、SBP、Cre、Killip、心停止、STT 偏位、心筋バイオマーカー
- Web 計算機必須

### 9-7. TIMI risk score
- 65 歳以上、CAD リスク因子 ≥3、既知の CAD、アスピリン 7 日以内、狭心症 2 回/24h、ST 偏位 ≥0.5mm、心筋バイオマーカー陽性
- 各 1 点

### 9-8. CURB-65 / A-DROP
- **CURB-65**：Confusion / Urea >7 mmol/L / RR ≥30 / BP <90/60 / Age ≥65
  - 0–1 外来、2 入院検討、≥3 重症
- **A-DROP（JRS）**：Age (男 ≥70, 女 ≥75)、Dehydration (BUN ≥21)、Respiration (SpO₂ ≤90)、Orientation、BP (SBP ≤90)
  - 0 軽症、1–2 中等症、3 重症、4–5 超重症

### 9-9. qSOFA / SOFA / SIRS
- **qSOFA**：意識変容、RR ≥22、SBP ≤100（≥2 で敗血症疑い）
- **SOFA**：6 臓器（呼吸/凝固/肝/循環/CNS/腎）0–4 点
- **SIRS**：体温 <36 or >38、HR >90、RR >20 or PaCO₂ <32、WBC <4 or >12k or bands >10%

### 9-10. NEWS2（英国標準）
- RR、SpO₂、酸素投与、体温、SBP、HR、意識レベル
- ≥5 で緊急対応、≥7 で ICU 検討

### 9-11. Ottawa Heart Failure Risk Scale
- 過去の CABG／COPD／心不全既往、SBP <110、心電図 acute ischemia、BUN >12、NT-proBNP >5000、Sat <90%、6 分間歩行など
- 高スコアで 14 日以内の serious event 予測

### 9-12. EHMRG（Emergency Heart Failure Mortality Risk Grade）
- 7 日以内の死亡予測。低リスク帰宅可能症例の同定

### 9-13. 気管挿管失敗予測（MACOCHA / LEMON）
- **LEMON**：Look / Evaluate 3-3-2 / Mallampati / Obstruction / Neck mobility

---

## 10. POCUS 詳細

### 10-1. BLUE protocol（Lichtenstein、Chest 2008）
6 ポイント（両側 upper BLUE、lower BLUE、PLAPS）で lung sliding、A/B-line、consolidation、胸水、lung point を評価。

| Profile | 所見 | 想定疾患 |
|---|---|---|
| **A** profile | 両側 A-line + sliding あり | COPD、喘息 |
| **A' ** profile | 両側 A-line + sliding なし | 気胸（lung point で確定） |
| **B** profile | 両側 B-line + sliding あり | 心原性肺水腫 |
| **B'** profile | 両側 B-line + sliding なし | 肺炎 |
| **A/B** profile | 片側 B-line | 肺炎 |
| **C** profile | consolidation（前胸部） | 肺炎 |
| **A + PLAPS** | + 後外側 consolidation/胸水 | 肺炎、胸水 |
| **A + DVT** | A profile + DVT 陽性 | PE |

感度 90.5%、特異度 93%（Chest 2008;134:117）

### 10-2. FoCUS（Focused Cardiac US）5 view
1. **Parasternal long axis (PLAX)**
2. **Parasternal short axis (PSAX)**
3. **Apical 4-chamber (A4C)**
4. **Subcostal 4-chamber**
5. **Subcostal IVC**

評価項目：
- LV size / EF（eyeballing で軽度低下・中等度・高度）
- RV size（RV/LV >1 で拡大、D-shape、McConnell 徴候）
- 心嚢液（前後、tamponade physiology：RA collapse in systole、RV collapse in diastole）
- IVC 径・呼吸性変動（<2.1cm + >50%変動 → RAP <10、>2.1cm + <50% → >15）
- 弁膜症の粗評価

### 10-3. RUSH protocol（**Pump / Tank / Pipes**）
- **Pump**：心収縮、心嚢液、RV strain
- **Tank**：IVC、Morison, splenorenal, pouch of Douglas（FAST）、肺（気胸、肺水腫、胸水）
- **Pipes**：大動脈（AAA、解離）、下肢 DVT

### 10-4. DVT 2-point compression US
- 総大腿静脈（鼠径下）と膝窩静脈で圧迫、圧潰不能 → DVT
- 感度 90%、特異度 95%

### 10-5. 気道 US
- 気管挿管確認（食道挿管の否定、"double tract sign"）
- 輪状甲状間膜位置確認

---

## 11. 画像戦略

### 11-1. CXR portable の系統的読影（ABCDEF）
- **A**irway：気管偏位、太さ
- **B**reathing：肺野、透過性、B-line
- **C**irculation：心陰影 CTR、大動脈弓
- **D**iaphragm：横隔膜位置、free air
- **E**dges：胸膜、costo-phrenic angle（deep sulcus sign = 気胸）
- **F**oreign / **F**racture：デバイス位置、肋骨骨折

### 11-2. CT の選択
| 適応 | プロトコル |
|---|---|
| PE 疑い | 造影 CT（CTPA、bolus tracking 肺動脈 100–150 HU） |
| 大動脈解離 | TR-CT（心電図同期）、entry site、branch involvement |
| AAA 破裂 | 造影 CT 腹部 |
| 肺炎詳細、間質性、無気肺 | 単純 CT 胸部（HRCT 追加） |
| 気胸 fine detail | 単純 CT 胸部 |
| 縦隔気腫、食道破裂 | 造影 CT 胸部 |

### 11-3. 心エコー正式
- LV/RV サイズ・機能、弁膜症、心嚢液、下大静脈、TAPSE、S'、Strain
- 疑うべき：AMI 合併症（VSD、papillary rupture、遊離壁破裂）、心筋炎、たこつぼ

### 11-4. 造影剤アレルギー・腎障害の考慮
- Cre >1.5 or eGFR <30 → リスク・ベネフィット、hydration
- ヨード禁忌 → V/Q スキャン（PE の代替）、MRI（解離）、経食道エコー

---

## 12. 疾患別ワークアップ

### 12-1. 肺塞栓（PE）
**フローチャート**
1. **PERC 8 項目全て陰性 + low pretest** → 除外
2. **Wells / Geneva で pretest** 判定
3. **YEARS + 年齢調整 D-dimer** で除外 or CTPA
4. CTPA 陽性 → 重症度分類（massive / submassive / low-risk）
5. **重症度分類**
   - **Massive**：SBP <90（15 分以上 or 昇圧要）→ 血栓溶解（tPA）
   - **Submassive**：血圧維持 + RV dysfunction or Trop 上昇 → 個別判断（catheter-directed thrombolysis）
   - **Low-risk**：PESI class I-II or sPESI 0 → 外来治療可（DOAC）
6. **PESI / sPESI** で予後推定
7. **抗凝固**：DOAC（アピキサバン 10 mg BID ×7 日 → 5 mg BID、リバーロキサバン 15 mg BID ×21 日 → 20 mg QD）、UFH、LMWH

### 12-2. ACS
1. **10 分以内 ECG**、STEMI 診断 → PCI 90 分以内目標
2. **hs-cTn 0/1h**
3. **HEART / GRACE / TIMI**
4. アスピリン 162–325 mg 咀嚼、P2Y12（Ticagrelor 180 mg or Prasugrel）、UFH or LMWH、硝酸薬、β-blocker、statin
5. モルヒネは慎重（P2Y12 吸収遅延）
6. 右室梗塞：硝酸薬・利尿薬避け、輸液
7. STEMI 疑いは造影 CT より先に **心臓カテ**

### 12-3. 急性心不全（AHF）
- **臨床型分類（Forrester、Nohria-Stevenson）**：wet/dry × warm/cold
- **CS 分類（Cotter）**：CS1 高血圧型（>140）、CS2 通常型、CS3 低血圧型、CS4 ACS、CS5 右心不全
- 治療（CS1）：**NPPV 早期**、硝酸薬 IV（ニトログリセリン 5–200 μg/min）、フロセミド 20–80 mg IV
- 治療（CS3）：昇圧・強心（ノルアド、ドブタミン）、機械的補助（IABP、Impella、V-A ECMO）
- 併存：AF、貧血、腎不全、感染、虚血のトリガー検索

### 12-4. 肺炎・敗血症
- **CAP / NHCAP / HAP** を区別（JRS 2024）
- **重症度**：A-DROP、CURB-65、qSOFA
- **バンドル（Surviving Sepsis 1 時間）**：Lactate、血培、広域抗菌薬、輸液（30 mL/kg 晶質液）、昇圧（MAP ≥65）
- 病原体同定：喀痰、血培、尿中抗原、PCR panel、SARS-CoV-2、インフル
- 抗菌薬（CAP 中等症入院）：CTRX 2 g q24 + アジスロマイシン 500 mg q24 or LVFX 500 mg q24
- 抗菌薬（重症 ICU）：CTRX or PIPC/TAZ + マクロライド / キノロン、耐性リスクで抗 MRSA / 抗緑膿

### 12-5. COPD 増悪
- 誘因：感染（ウイルス > 細菌）、大気汚染、心不全合併、PE 合併（GOLD 推奨で D-dimer 考慮）
- **SABA + SAMA（サルブタモール + イプラトロピウム）** 吸入
- **プレドニゾロン 40 mg PO ×5 日** or メチルプレドニゾロン IV
- 抗菌薬：Anthonisen 3 徴（呼吸困難増、痰量増、膿性痰）で適応
- **NPPV（IPAP 12–15 / EPAP 5）** で挿管率 50% 低下（ATS/ERS 2017）
- 酸素目標 88–92%、Venturi mask で FiO₂ 制御

### 12-6. 喘息発作
- **重症度**：PEF % predicted、SpO₂、話せるか、意識、silent chest
- **治療**：SABA neb 反復（サルブタモール 2.5–5 mg q20min ×3）、イプラトロピウム neb 併用、**全身ステロイド**（PSL 40–50 mg PO or メチルプレドニゾロン 40–80 mg IV）
- 追加：**MgSO₄ 2 g IV 20 分**（重症）、アドレナリン IM（0.3–0.5 mg、アナフィラキシー鑑別）
- **挿管準備**：silent chest、意識障害、CO₂ 上昇（正常化も危険）、疲労
- ケタミン、揮発性麻酔薬、ECMO 検討

### 12-7. 気胸
- 診断：CXR（deep sulcus sign, lucency）、CT、POCUS（lung sliding 消失、lung point）
- **緊張性気胸**：即減圧（第 2 肋間 midclavicular or 第 4/5 肋間 anterior axillary、14G）
- **小・症候軽微**：観察 or 吸引
- **中〜大・症状あり**：胸腔ドレーン（14–20 Fr）

### 12-8. 大動脈解離
- **Stanford A（上行）**：緊急手術
- **Stanford B（下行）**：降圧（HR 60、SBP 100–120）、疼痛管理、合併症（malperfusion、破裂）で TEVAR
- 降圧：**エスモロール or ランジオロール（β1 選択）** 先行 → ニカルジピン
- IRAD、ADD-RS（Aortic Dissection Detection Risk Score）活用

### 12-9. 心タンポナーデ
- Beck 三徴（低血圧、JVD、muffled heart sound）は約 10–40% でしか揃わない
- **POCUS 決め手**：RA/RV collapse、IVC plethora、pulsus paradoxus
- 心嚢穿刺（subxiphoid、apical、parasternal）、緊急 → 外科手術

### 12-10. アナフィラキシー
- 診断（Sampson criteria 満たす 1 つ）
- **アドレナリン 0.3–0.5 mg IM 大腿外側**（初動、5–15 分毎反復可）
- H1（クロルフェニラミン 10 mg IV）、H2（ラニチジン 50 mg IV）、ステロイド（ヒドロコルチゾン 200 mg IV）
- 気道確保：早期挿管閾値下げる、外科的気道準備
- 二相反応 4–24 時間後に注意 → 少なくとも 4–6 時間観察

### 12-11. 上気道閉塞
- Angioedema（ACE-I 関連 → **イカチバント、C1 esterase inhibitor** 適応）
- 喉頭蓋炎：X 線 thumb sign、耳鼻科・麻酔科同席で気道確保
- 異物：Heimlich、直接喉頭鏡下摘出、緊急気管切開

### 12-12. 代謝性アシドーシス
- **DKA**：輸液 → K 補正 → インスリン 0.1 U/kg/h、bicarbonate は pH <6.9 のみ
- **乳酸アシドーシス**：原因治療（敗血症、虚血、CO、シアン、メトホルミン）
- **サリチル酸中毒**：尿アルカリ化（NaHCO₃）、血液透析（>100 mg/dL、意識障害、腎障害）
- **中毒**：POISONDEX、中毒 110 番

### 12-13. 神経筋
- %VC <15 mL/kg、NIF <-20 → 挿管閾値
- GBS：血漿交換、IVIG、脱髄評価（NCS）
- MG クリーゼ：ChE 阻害薬中止、血漿交換 or IVIG、感染治療

---

## 13. 治療介入

### 13-1. 酸素デバイス
| デバイス | FiO₂ | 適応 |
|---|---|---|
| 経鼻カニュラ 1–6 L | 24–44% | 軽度 |
| Simple mask 6–10 L | 40–60% | 中等度 |
| Reservoir mask 10–15 L | 80–95% | 重度 |
| Venturi | 24–60%（固定） | COPD、精密制御 |
| HFNC | 21–100%、流量 20–60 L/min | Type I、抜管後、COVID |
| NPPV（CPAP / BiPAP） | ~100%、圧サポート | AHF、COPD、拒否ない意識清明 |
| 挿管 IMV | 全域 | ARDS、意識障害、疲労 |

### 13-2. HFNC 設定
- 開始：流量 40–60 L/min、FiO₂ SpO₂ ≥94% 目標に調節
- **ROX index = (SpO₂/FiO₂) / RR**、2 h で <2.85、6 h で <3.47、12 h で <3.85 は挿管予測（Roca ICM 2019）

### 13-3. NPPV（CPE：CPAP or BiPAP）
- CPAP：8–12 cmH₂O
- BiPAP：IPAP 12–15、EPAP 5、RR back-up 12
- COPD：IPAP 10–15、EPAP 4–5、PS 10 差
- 禁忌：意識障害、嘔吐、大量分泌、循環動態不安定、顔面外傷

### 13-4. 挿管準備（RSI）
- **前酸素化 3 分 or 8 深呼吸**、apneic oxygenation（HFNC or NC 15L）
- 鎮静：ケタミン 1–2 mg/kg（喘息、ショックで有利）、エトミデート 0.3 mg/kg、プロポフォール 1.5–2.5 mg/kg
- 筋弛緩：ロクロニウム 1.2 mg/kg（RSI 用量）、スキサメトニウム 1.5 mg/kg（高 K、熱傷、慢性神経筋で禁忌）
- チューブ：男性 8.0、女性 7.5（内径）、深さ = 声帯下 3–5 cm
- 確認：EtCO₂ 4 波形、聴診、CXR

### 13-5. 主要薬剤（ER 頻用）
| 薬剤 | 適応 | 用量 |
|---|---|---|
| アスピリン | ACS | 162–325 mg 咀嚼 |
| ニトログリセリン | ACS、AHF、CS1 | 5–200 μg/min IV、舌下 0.3 mg |
| フロセミド | AHF、うっ血 | 20–80 mg IV（普段量の 1–2.5×） |
| モルヒネ | ACS 疼痛 | 2–4 mg IV（呼吸抑制注意） |
| アドレナリン | アナフィラキシー | 0.3–0.5 mg IM 5–15 分毎 |
| アドレナリン | CPA | 1 mg IV 3–5 分毎 |
| ヒドロコルチゾン | 副腎不全、喘息、アナフィラキシー | 100–200 mg IV |
| メチルプレドニゾロン | 重症喘息、COPD | 40–125 mg IV |
| MgSO₄ | 重症喘息、torsades | 2 g IV 20 分 |
| アデノシン | SVT | 6 mg → 12 mg IV 急速 |
| アミオダロン | VT、AF | 150 mg IV 10 分 → 1 mg/min |
| ノルアドレナリン | 敗血症・心原性ショック | 0.05–1 μg/kg/min（MAP ≥65） |
| ドブタミン | 心原性ショック（血圧そこそこ） | 2–20 μg/kg/min |
| ヘパリン | PE、ACS | 60–80 U/kg bolus → 12–18 U/kg/h |
| tPA（アルテプラーゼ） | 大 PE | 100 mg / 2 h（50 mg /15 min → 50 mg/1.5h） |
| ケタミン | 挿管、痛み | 1–2 mg/kg IV、鎮痛 0.3 mg/kg |
| ミダゾラム | 鎮静 | 0.05–0.1 mg/kg IV |
| プロポフォール | 鎮静 | 導入 1.5–2.5、維持 1–4 mg/kg/h |
| ロクロニウム | RSI | 1.0–1.2 mg/kg IV |
| デクスメデトミジン | 挿管後、DEX 呼吸抑制なし | 0.2–0.7 μg/kg/h |

---

## 14. 特殊集団

### 14-1. 妊婦
- PE リスク 5 倍、産褥 20 倍
- CT-PE Pregnancy（NEJM 2019）：YEARS + trimester 別 D-dimer
- 造影 CT は胎児被曝小、必要なら実施
- 治療：LMWH（妊娠中の第一選択、DOAC・ワーファリン禁）
- 周産期心筋症：分娩前後 1 か月〜産後 5 か月の HF

### 14-2. 高齢者
- 症状 atypical：呼吸困難のみ、意識障害、失神
- PE は失神で来ることが多い（Prandoni NEJM 2016;375:1524）
- BNP・トロポニン は基礎値高い、動態変化を重視
- せん妄合併、多剤併用の確認
- **見逃しコスト大**：閾値を下げる

### 14-3. 透析患者
- 心不全、体液貯留、高 K、代謝性アシドーシス
- 心筋障害（uremic cardiomyopathy）、心膜炎、心タンポナーデ
- BNP・トロポニンの解釈慎重
- 造影 CT：透析日で無問題（すでに腎機能ゼロ）
- 緊急透析適応：**AEIOU**（Acidosis、Electrolyte、Ingestion、Overload、Uremia）

### 14-4. 免疫不全（HIV、ステロイド、抗癌剤）
- **PCP、真菌、CMV、結核** を鑑別
- LDH 高値、KL-6、β-D グルカン、GM 抗原
- 造影 CT・気管支鏡低閾値
- 経験的：TMP-SMX + ステロイド

### 14-5. 精神疾患既往
- 過換気症候群は **除外診断**
- 他疾患見逃しやすい：ACS、PE、代謝性
- SpO₂・ABG・心電図・BNP・D-dimer を最低限確認してから機能性と結論

### 14-6. 抗凝固薬・DAPT 内服者
- 出血・血胸・心タンポナーデを念頭
- 逆転薬：ワーファリン → PCC + Vit K、DOAC → イダルシズマブ（ダビガトラン）、アンデキサネットα（Xa 阻害薬）

---

## 15. Disposition

### 15-1. 帰宅可の条件
- 明確な軽症診断（機能性、上気道炎、軽度気管支炎）
- バイタル安定（room air SpO₂ ≥95%、RR <20、HR 60–100、SBP 100–160）
- 独居でない or 再診確保
- 症状改善傾向、経口摂取可
- HEART ≤3、PESI class I、CURB-65 0–1、A-DROP 0

### 15-2. 経過観察入院（ER 観察病床）
- 症状 persistent
- 診断確定せず追加検査待ち
- 治療反応評価要（NPPV、利尿）
- 独居高齢、認知症、社会背景

### 15-3. 一般入院
- CAP with A-DROP ≥1、AHF Killip II、COPD 増悪
- 酸素投与要
- PE low-risk で入院適応（施設プロトコル）

### 15-4. HCU / ICU
- SpO₂ <90%（O₂ 投与下）、qSOFA ≥2、Lac ≥4
- 意識障害、NIV/IMV 要
- STEMI、大 PE、AAD、心原性ショック
- 敗血症性ショック、DKA severe
- Airway 不安定

### 15-5. 帰宅時説明（Safety-netting）
- 再受診基準：呼吸困難増悪、SpO₂ 低下、胸痛、失神、下肢腫脹、血痰
- フォロー予約日
- 服薬指導、吸入手技確認
- 禁煙、ワクチン（肺炎球菌、インフル、COVID）

---

## 16. Pitfall 集

1. **BNP 単独では診断不能**：肥満で低く、AF・腎不全・高齢で高い
2. **D-dimer 陽性 ≠ PE**：術後、妊娠、感染、悪性で上昇。**除外専用**
3. **CXR 正常でも PE / 早期心不全 / 早期肺炎あり得る**
4. **SpO₂ 正常でも A-aDO₂ 開大あれば PE を疑う**
5. **COPD で高濃度 O₂ → CO₂ ナルコーシス**：target 88–92%
6. **心タンポナーデは血圧正常でも起こる**（急性・少量）
7. **アナフィラキシーは皮疹なしでも呼吸困難で来る**
8. **高齢者の PE は失神・意識障害プレゼン**
9. **Silent chest** = 重症喘息 or 緊張性気胸
10. **喘息発作で PaCO₂ 正常化は挿管準備サイン**
11. **STEMI は V4R（右側胸部誘導）を必ず確認**（下壁 MI + 右室梗塞）
12. **急性心筋炎は心不全・不整脈で来る**、若年で ST 上昇
13. **メトホルミン + 造影 CT + 腎障害** → 乳酸アシドーシス
14. **透析患者の胸痛は心筋障害以外に心膜炎・タンポナーデ**
15. **NPPV は意識障害・嘔吐で禁忌**
16. **HFNC の ROX index を経時的に**、悪化なら早期挿管
17. **PCT は初期に陰性でも 4–6 時間で追跡再検**
18. **hs-cTn 動態変化なしでも臨床的高リスクは経過観察**
19. **CO 中毒は SpO₂ 正常** → cooximeter で SaO₂ を測る
20. **食道破裂（Boerhaave）**：嘔吐後の胸背部痛、Hamman sign、縦隔気腫
21. **たこつぼ心筋症**：EF 低下、心尖 balloon、閉経後女性、精神ストレス後、troponin 軽度上昇
22. **周産期心筋症**：分娩前 1 か月〜産後 5 か月、EF <45%
23. **サルコイドーシス／IPF**：慢性経過だが増悪で ER 受診あり
24. **薬剤性肺障害**：ブレオマイシン、アミオダロン、免疫チェックポイント阻害薬、EGFR-TKI
25. **肺高血圧クリーゼ**：CTEPH、原発性、失神、右心不全
26. **周術期／術後 呼吸困難**：無気肺、PE、輸血関連（TRALI）、感染
27. **輸血関連呼吸困難**：TRALI（<6h）、TACO（>6h、うっ血）
28. **粟粒結核**：発熱、労作時呼吸困難、CXR 粟粒影
29. **HIT（ヘパリン誘発性血小板減少症）+ 血栓** を PE で見逃さない
30. **精神性過換気の"診断"は他疾患完全除外後**

---

## 17. Japan-specific（保険適応と診療報酬）

- **hs-cTn（TnI、TnT）**：D007 血液化学検査、AMI 疑いで算定
- **BNP / NT-proBNP**：D008、月 1 回算定（心不全診療で例外）
- **プロカルシトニン（PCT）**：D007 27、敗血症疑いで算定
- **D-dimer**：D006 21
- **血液培養**：D018 2 セット標準（1 セットは false negative 多い）
- **尿中肺炎球菌抗原・レジオネラ抗原**：D012
- **SARS-CoV-2 PCR / 抗原**：診療報酬点数変動、最新確認
- **CTPA・造影 CT**：E200・E202、造影加算
- **NPPV**：J045-2、算定要件（AHF、COPD 等）
- **HFNC**：J045
- **ECMO**：J045-3、施設基準要
- **A-DROP・CURB-65**：日本呼吸器学会 CAP ガイドライン 2024 で標準
- **J-SSCG 2024**：敗血症診療、1 時間バンドル準拠
- **循環器 GL 2021**：急性・慢性心不全診療ガイドライン

---

## 18. 参考文献

### 教科書・総説
1. Tintinalli JE, et al. **Tintinalli's Emergency Medicine: A Comprehensive Study Guide**, 9th ed. McGraw-Hill; 2020. Ch.62 Dyspnea.
2. Walls RM, et al. **Rosen's Emergency Medicine**, 10th ed. Elsevier; 2023. Ch.22 Dyspnea.
3. Marx JA, et al. **Rosen's Emergency Medicine**, 9th ed. Ch. 22 & 71–74.
4. Parrillo JE, Dellinger RP. **Critical Care Medicine: Principles of Diagnosis and Management in the Adult**, 5th ed. Elsevier; 2019.

### 呼吸不全・POCUS
5. Lichtenstein DA, Mezière GA. Relevance of lung ultrasound in the diagnosis of acute respiratory failure: the BLUE protocol. **Chest**. 2008;134(1):117-125. doi:10.1378/chest.07-2800
6. Perera P, et al. The RUSH exam: Rapid Ultrasound in SHock. **Emerg Med Clin North Am**. 2010;28(1):29-56.
7. Volpicelli G, et al. International evidence-based recommendations for point-of-care lung ultrasound. **Intensive Care Med**. 2012;38(4):577-591.
8. Roca O, et al. An index combining respiratory rate and oxygenation to predict outcome of nasal high-flow therapy (ROX index). **Am J Respir Crit Care Med**. 2019;199(11):1368-1376.

### PE
9. Konstantinides SV, et al. 2019 ESC Guidelines for the diagnosis and management of acute pulmonary embolism. **Eur Heart J**. 2020;41(4):543-603.
10. van der Hulle T, et al. Simplified diagnostic management of suspected pulmonary embolism (YEARS study). **Lancet**. 2017;390(10091):289-297.
11. Righini M, et al. Age-adjusted D-dimer cutoff levels to rule out pulmonary embolism: ADJUST-PE. **JAMA**. 2014;311(11):1117-1124.
12. Kline JA, et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism (PERC). **J Thromb Haemost**. 2004;2(8):1247-1255.
13. Wells PS, et al. Derivation of a simple clinical model to categorize patients probability of pulmonary embolism. **Thromb Haemost**. 2000;83(3):416-420.
14. van der Pol LM, et al. Pregnancy-adapted YEARS algorithm for diagnosis of suspected pulmonary embolism. **N Engl J Med**. 2019;380(12):1139-1149.
15. Prandoni P, et al. Prevalence of pulmonary embolism among patients hospitalized for syncope. **N Engl J Med**. 2016;375(16):1524-1531.
16. Meyer G, et al. Fibrinolysis for patients with intermediate-risk pulmonary embolism (PEITHO). **N Engl J Med**. 2014;370(15):1402-1411.

### ACS
17. Collet JP, et al. 2020 ESC Guidelines for NSTE-ACS. **Eur Heart J**. 2021;42(14):1289-1367.
18. Ibanez B, et al. 2017 ESC Guidelines for STEMI. **Eur Heart J**. 2018;39(2):119-177.
19. Six AJ, Backus BE, Kelder JC. Chest pain in the emergency room: value of the HEART score. **Neth Heart J**. 2008;16(6):191-196.
20. Mueller C, et al. Rapid rule out of AMI: novel biomarker-based strategies (0/1h algorithm). **Eur Heart J Acute Cardiovasc Care**. 2017;6(3):218-222.
21. Reichlin T, et al. One-hour rule-out and rule-in of AMI using high-sensitivity cardiac troponin T. **Arch Intern Med**. 2012;172(16):1211-1218.
22. Neumann JT, et al. Application of high-sensitivity troponin in suspected myocardial infarction. **N Engl J Med**. 2019;380(26):2529-2540.

### 心不全
23. McDonagh TA, et al. 2021 ESC Guidelines for the diagnosis and treatment of acute and chronic heart failure. **Eur Heart J**. 2021;42(36):3599-3726.
24. Januzzi JL, et al. The N-terminal Pro-BNP investigation of dyspnea in the emergency department (PRIDE). **Am J Cardiol**. 2005;95(8):948-954.
25. Maisel AS, et al. Rapid measurement of B-type natriuretic peptide in the emergency diagnosis of heart failure (Breathing Not Properly). **N Engl J Med**. 2002;347(3):161-167.
26. Stiell IG, et al. A risk scoring system to identify emergency department patients with heart failure at high risk for serious adverse events (Ottawa HFRS). **Acad Emerg Med**. 2013;20(1):17-26.
27. Lee DS, et al. Prediction of heart failure mortality in emergent care: a cohort study (EHMRG). **Ann Intern Med**. 2012;156(11):767-775.

### 肺炎・敗血症
28. Metlay JP, et al. Diagnosis and Treatment of Adults with Community-acquired Pneumonia. Official ATS/IDSA Clinical Practice Guideline. **Am J Respir Crit Care Med**. 2019;200(7):e45-e67.
29. Singer M, et al. The Third International Consensus Definitions for Sepsis and Septic Shock (Sepsis-3). **JAMA**. 2016;315(8):801-810.
30. Evans L, et al. Surviving Sepsis Campaign: International Guidelines for Management of Sepsis and Septic Shock 2021. **Crit Care Med**. 2021;49(11):e1063-e1143.
31. Levy MM, et al. The Surviving Sepsis Campaign Bundle: 2018 update. **Intensive Care Med**. 2018;44(6):925-928.
32. 日本呼吸器学会. **成人肺炎診療ガイドライン 2024**（A-DROP, NHCAP を含む）.
33. 日本救急医学会・集中治療医学会. **日本版敗血症診療ガイドライン 2024（J-SSCG 2024）**.

### COPD・喘息
34. Global Initiative for Chronic Obstructive Lung Disease. **GOLD 2024 Report**.
35. Global Initiative for Asthma. **GINA 2024 Report**.
36. Rochwerg B, et al. Official ERS/ATS clinical practice guidelines: noninvasive ventilation for acute respiratory failure. **Eur Respir J**. 2017;50(2):1602426.

### 大動脈解離
37. Erbel R, et al. 2014 ESC Guidelines on the diagnosis and treatment of aortic diseases. **Eur Heart J**. 2014;35(41):2873-2926.
38. Rogers AM, et al. Sensitivity of the aortic dissection detection risk score (ADD-RS). **Circulation**. 2011;123(20):2213-2218.

### 酸素・気管挿管
39. O'Driscoll BR, et al. BTS guideline for oxygen use in adults in healthcare and emergency settings. **Thorax**. 2017;72(Suppl 1):ii1-ii90.
40. Frat JP, et al. High-flow oxygen through nasal cannula in acute hypoxemic respiratory failure (FLORALI). **N Engl J Med**. 2015;372(23):2185-2196.
41. Brown CA, Sakles JC. **The Walls Manual of Emergency Airway Management**, 5th ed. Wolters Kluwer; 2018.

### 中毒・その他
42. Boyer EW. Management of opioid analgesic overdose. **N Engl J Med**. 2012;367(2):146-155.
43. Prahlow JA. Salicylate toxicity. **Am J Forensic Med Pathol**. 2020;41(1):e1-e6.
44. Weaver LK. Carbon monoxide poisoning. **N Engl J Med**. 2009;360(12):1217-1225.

### 日本国内ガイドライン
45. 日本循環器学会. **急性・慢性心不全診療ガイドライン（2017 年改訂版・2021 フォーカスアップデート）**.
46. 日本循環器学会. **急性冠症候群ガイドライン（2018 年改訂版）**.
47. 日本循環器学会. **肺血栓塞栓症および深部静脈血栓症の診断、治療、予防に関するガイドライン（2017 年改訂版）**.
48. 日本高血圧学会. **高血圧治療ガイドライン 2019（JSH2019）**.
49. 日本アレルギー学会. **アナフィラキシーガイドライン 2022**.
50. 日本呼吸器学会・日本結核・非結核性抗酸菌症学会. **成人肺炎診療ガイドライン 2024**.

---

## 付録 A：呼吸困難 ER チェックリスト（印刷用）

```
□ トリアージ：SpO2___% RR___ HR___ BP___/___ (両上肢) T___℃ GCS___ Borg___
□ 即動：酸素、モニタ、静脈路×2、血糖、ECG、CXR、ABG(Lac,COHb,MetHb)、POCUS
□ 病歴：発症様式、既往、内服、旅行、Red flag
□ 身体：皮膚、JVD、胸郭対称、聴診、下肢腫脹、神経
□ 採血：CBC / 生化 / CRP / PCT / hs-cTn / NT-proBNP / PT-APTT-Fbg / D-dimer / 血培×2
□ 感染：SARS-CoV-2 / インフル / 尿中抗原
□ スコア：Wells__ PERC__ YEARS__ HEART__ CURB-65__ A-DROP__ qSOFA__ NEWS2__
□ 追加画像：CTPA / TR-CT / 心エコー
□ 治療：O2目標__% デバイス__ 薬剤__
□ Disposition：帰宅/観察/一般/HCU/ICU 理由__
□ Safety-netting：再受診基準説明・書面
```

## 付録 B：スコア web 計算機
- MDCalc.com（HEART, Wells, PERC, YEARS, CURB-65, PESI, sPESI, GRACE, TIMI, ADD-RS）
- ESC アプリ（ESC pocket guidelines）
