# book-skill

Books converted into agent skills with [book-to-skill](https://github.com/virgiliojr94/book-to-skill). Each book lives in its own folder as a self-contained skill (SKILL.md + chapters/ + glossary / patterns / cheatsheet).

## Skills

| Folder | Source book |
|---|---|
| [ai-a-modern-approach](ai-a-modern-approach/) | 《人工智能：现代方法（第4版）》 (Artificial Intelligence: A Modern Approach, 4th ed.) — Stuart Russell & Peter Norvig |
| [math/linear-algebra](math/linear-algebra/) | 《线性代数及其应用（原书第6版）》 (Linear Algebra and Its Applications, 6th ed.) — David C. Lay, Steven R. Lay & Judi J. McDonald |
| [math/princeton-calculus](math/princeton-calculus/) | 《普林斯顿微积分读本（第2版）》 (The Calculus Lifesaver) — Adrian Banner |
| [math/tongji-calculus](math/tongji-calculus/) | 《高等数学（第八版）上、下册》 (Higher Mathematics, 8th ed.) — 同济大学数学科学学院 |

## Install

```bash
npx skills add https://github.com/DarkModest/book-skill --skill ai-a-modern-approach
npx skills add https://github.com/DarkModest/book-skill --skill linear-algebra
npx skills add https://github.com/DarkModest/book-skill --skill princeton-calculus
npx skills add https://github.com/DarkModest/book-skill --skill tongji-calculus
```

Note: all content is synthesized chapter summaries and study aids, not the original book text.
