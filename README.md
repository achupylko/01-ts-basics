# React + Next.js Course — Module 1 (TypeScript Basics)

## 📘 Опис проєкту

Цей репозиторій містить практичні завдання **1 модуля курсу React.js +
Next.js**, який присвячений вивченню **TypeScript** та його використанню разом
із JavaScript.

Метою модуля є засвоєння базових принципів **типізації**, налаштування
середовища та використання TypeScript для написання більш безпечного та
зрозумілого коду.

---

## 🎯 Результати навчання (Module 1)

У цьому модулі ти навчишся:

- Розуміти що таке **TypeScript** і чим він корисний;
- Встановлювати та налаштовувати середовище для роботи з TS;
- Працювати з **основними типами даних**;
- Типізувати **функції**;
- Типізувати **Promise**.

Після завершення цього модуля ти зможеш:

✔️ Типізувати JavaScript код  
✔️ Розуміти базову систему типів TypeScript  
✔️ Писати безпечніший та більш передбачуваний код

---

## 🧩 Структура проєкту

```
01-ts-basics/
│
├── node_modules/
├── public/
├── src/
│   ├── task-1.ts
│   ├── task-2.ts
│   ├── task-3.ts
│   ├── task-4.ts
│   ├── task-5.ts
│   ├── task-6.ts
│   ├── task-7.ts
│   └── task-8.ts
│
├── .gitignore
├── .prettierrc.json
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.json
└── README.md
```

---

## 📂 Завдання

### Task 1 – Basic Types

Робота з базовими типами TypeScript:

- `string`
- `number`
- `boolean`
- `null`
- `undefined`

---

### Task 2 – Object Types

Типізація об'єктів.

```ts
type User = {
  name: string;
  age: number;
};
```

---

### Task 3 – Arrays

Типізація масивів.

```ts
const numbers: number[] = [1, 2, 3];
```

---

### Task 4 – Functions

Типізація функцій.

```ts
function add(a: number, b: number): number {
  return a + b;
}
```

---

### Task 5 – Union Types

Використання об'єднаних типів.

```ts
let id: string | number;
```

---

### Task 6 – Type Aliases

Створення власних типів.

```ts
type Product = {
  title: string;
  price: number;
};
```

---

### Task 7 – Promise Typing

Типізація асинхронних операцій.

```ts
function fetchData(): Promise<string> {
  return Promise.resolve('data');
}
```

---

### Task 8 – Advanced Typing

Комбінування різних підходів типізації та використання типів разом.

---

## 🧠 Використані технології

- **TypeScript**
- **JavaScript (ES6+)**
- **Node.js**
- **NPM**
- **HTML5**
- **Prettier**
- **Git / GitHub**

---

## ⚙️ Налаштування TypeScript

Основні параметри конфігурації знаходяться у файлі:

```
tsconfig.json
```

Приклад важливих налаштувань:

```json
{
  "compilerOptions": {
    "target": "ES6",
    "module": "ESNext",
    "strict": true,
    "moduleResolution": "Node"
  }
}
```

---

## 🚀 Як запустити проєкт

### 1️⃣ Встановити залежності

```bash
npm install
```

### 2️⃣ Запустити TypeScript компіляцію

```bash
npx tsc
```

### 3️⃣ Відкрити проєкт у браузері

Відкрий файл:

```
index.html
```

---

## 💡 Best Practices

✅ Використовуй `strict` режим у TypeScript  
✅ Типізуй функції та значення, що вони повертають  
✅ Використовуй `type` або `interface` для складних структур  
✅ Уникай використання `any`

---

## 👨‍💻 Автор

**Артем Чупилко**  
Студент курсу **React.js + Next.js Developer**
