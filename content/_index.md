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
      text: |- # ↓↓↓ 句読点を変更したテキスト ↓↓↓
        名古屋大学大学院 情報学研究科 博士課程学生の古川樹です.
        
        主な研究分野は人工生命(Artificial Life)で, 生命のようなシステムが持つ原理の理解を目指しています.
        現在は特に, 連続値セルオートマトンであるLeniaモデルに注目し, そのダイナミクスや振る舞いについて研究を進めています.
    design:
      columns: '1'
# --- 以下に、今後表示したい他のセクションを必要に応じて追加 ---

---