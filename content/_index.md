---
title: ""
date: 2022-10-24 # この日付は元のままです
type: landing

sections:
# --- Section 1: Biography ---
  - block: resume-biography-3
    id: about # (任意) セクションID
    content:
      username: admin
    # design などは必要なら後で追加・調整 (今は最小限)

# --- Section 2: My Research (Markdown Block) ---
  - block: markdown
    id: research # (任意) セクションID
    content:
      title: '📚 My Research' # タイトル
      subtitle: ''
      text: |- # 句読点を変更したテキスト
        名古屋大学大学院 情報学研究科 博士課程学生の古川樹です.
        
        主な研究分野は人工生命(Artificial Life)で, 生命のようなシステムが持つ原理の理解を目指しています.
        現在は連続値セルオートマトンである『Lenia』に注目し, そのダイナミクスや振る舞いについて研究を進めています.
    design:
      columns: '1'

# --- Section 3: Background & Qualifications (Markdown Block) ---
  - block: markdown
    id: background # (任意) セクションID
    content:
      title: '経歴・資格' # セクションタイトル
      text: |- # ↓↓↓ 箇条書きに変更したテキスト ↓↓↓
        * 2023年3月: 信州大学 繊維学部 機械ロボット学科 バイオエンジニアリングコース 卒業 (学士(工学))
        * 2025年3月: 名古屋大学大学院 情報学研究科 複雑系科学専攻 創発システム論講座 修了 (修士(情報学))
        * 保有資格: 中学校・高等学校教諭一種免許状（理科）
    design:
      columns: '1'
# --- 以下に、今後表示したい他のセクションを必要に応じて追加 ---

---