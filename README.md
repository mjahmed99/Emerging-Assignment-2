## 🧠 Hooks Used

### 1. `useState`  
Used to manage internal state of tasks, theme, timer values, and toggles.

### 2. `useEffect`  
Handles side effects like LocalStorage syncing, timer countdown logic, and theme updates on load.

### 3. `useContext`  
Used to share theme and task stats across components efficiently using `ThemeContext` and `TaskStatsContext`.

### 4. `useReducer`  
(Optional: If implemented) To manage complex state transitions in timer logic or tasks.

### 5. `useRef`  
Used to reference the timer interval ID without causing unnecessary re-renders.

### 6. `useCallback` / `useMemo`  
Used for performance optimization, preventing unnecessary renders.

### 7. `useLocalStorage` (Custom Hook)  
```js
const [value, setValue] = useLocalStorage('key', defaultValue);
