# ***насби Tailwind дар Ubuntu*** 
## ҚАДАМИ 1: Санҷ — Tailwind умуман насб шудааст ё не

Дар дохили папкаи проект:

```bash
ls node_modules/.bin | grep tailwind
```

Агар **ҳеҷ чиз барнагардонад** → Tailwind CLI нест 

---

## ҚАДАМИ 2: Насби ДУРУСТИ CLI (ҳатмӣ)

```bash
npm install -D @tailwindcss/cli
```

Санҷ:

```bash
ls node_modules/.bin | grep tailwind
```

Бояд бинӣ:

```
tailwindcss
```

---

## ҚАДАМИ 3: Командаи ЯГОНАИ ДУРУСТ

```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

---

## ЧАРО ҲОЗИР ИН КОР МЕКУНАД?

* `@tailwindcss/cli` насб шуд
* `npx` executable-ро аз `node_modules/.bin` меёбад
* Ubuntu OK 

---