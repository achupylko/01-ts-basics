# React + Next.js Course — Module 1 (TypeScript Basics)

## 📘 Опис проєкту

Цей репозиторій містить практичні завдання **1 модуля курсу React.js +
Next.js**, який присвячений вивченню **TypeScript** та його використанню разом
із JavaScript.

Проєкт ініціалізований та зібраний за допомогою **Vite**, що забезпечує швидке
середовище розробки, миттєве оновлення модулів (HMR) та швидку збірку проєкту.

Метою модуля є засвоєння базових принципів **типізації**, налаштування
середовища та використання TypeScript для написання більш безпечного та
зрозумілого коду.

---

## 🎯 Результати навчання (Module 1)

У цьому модулі ти навчишся:

- Розуміти що таке **TypeScript** і чим він корисний
- Встановлювати та налаштовувати середовище для роботи з **TypeScript + Vite**
- Працювати з **основними типами даних**
- Типізувати **функції**
- Типізувати **Promise**
- Використовувати TypeScript для покращення якості JavaScript‑коду

Після завершення модуля ти зможеш:

✔️ Типізувати JavaScript код  
✔️ Розуміти базову систему типів TypeScript  
✔️ Працювати з TypeScript у сучасному середовищі розробки (Vite)

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

### Task 1 — Basic Types

Практика роботи з базовими типами:

- `string`
- `number`
- `boolean`
- `null`
- `undefined`

---

### Task 2 — Object Types

```ts
type User = {
  name: string;
  age: number;
};
```

---

### Task 3 — Arrays

```ts
const numbers: number[] = [1, 2, 3];
```

---

### Task 4 — Functions

```ts
function add(a: number, b: number): number {
  return a + b;
}
```

---

### Task 5 — Union Types

```ts
let id: string | number;
```

---

### Task 6 — Type Aliases

```ts
type Product = {
  title: string;
  price: number;
};
```

---

### Task 7 — Promise Typing

```ts
function fetchData(): Promise<string> {
  return Promise.resolve('data');
}
```

---

### Task 8 — Advanced Typing

Комбінування різних підходів типізації та використання типів разом.

---

## 🧠 Використані технології

- **TypeScript**
- **Vite**
- **JavaScript (ES6+)**
- **Node.js**
- **NPM**
- **HTML5**
- **Prettier**
- **Git / GitHub**

---

## ⚙️ Конфігурація TypeScript

Основні параметри знаходяться у файлі:

```
tsconfig.json
```

Приклад конфігурації:

```json
{
  "compilerOptions": {
    "target": "ESNext",
    "module": "ESNext",
    "strict": true,
    "moduleResolution": "Node"
  }
}
```

---

## 🚀 Запуск проєкту

### 1. Встановити залежності

```bash
npm install
```

### 2. Запустити dev‑сервер Vite

```bash
npm run dev
```

### 3. Відкрити проєкт у браузері

Зазвичай Vite запускає сервер за адресою:

```
http://localhost:5173
```

---

## 💡 Best Practices

✅ Використовуй `strict` режим у TypeScript  
✅ Типізуй параметри та return значення функцій  
✅ Уникай використання `any`  
✅ Використовуй `type` або `interface` для складних структур

---

## 👨‍💻 Автор

**Артем Чупилко**  
Студент курсу **React.js + Next.js Developer**
