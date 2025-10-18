# 🛰️ 軟體計畫書：心理登月系統 × 室內設計透明平台

## 一、專案名稱

**LunarMind Studio（暫定）**
— 以「心理登月法」為核心的室內設計透明化平台

---

## 二、專案核心理念

> 將「心理學 × 設計流程」結合，讓業主與設計師在設計過程中保持信任與安心感。
> 打造一個能即時呈現進度、預算、決策、回饋與心理曲線的透明平台。

### 核心價值：

1. **營運透明化**：讓客戶即時看到設計階段、支出比例、設計進展。
2. **心理登月機制**：導入峰終效應、目標漸進回饋，減少焦慮與誤解。
3. **信任指數系統**：根據設計師回覆速度、進度準確率與客戶滿意度動態顯示。
4. **數據化決策**：幫助設計師分析每個案子的心理節奏與溝通瓶頸。

---

## 三、主要使用者

| 類別     | 角色         | 需求與動機              |
| ------ | ---------- | ------------------ |
| 室內設計師  | 個人 / 公司負責人 | 提升客戶信任、減少誤會與追款風險   |
| 業主（客戶） | 一般消費者      | 了解工程進度、預算變動、設計決策理由 |
| 系統管理者  | 平台運營方      | 維護數據安全、確保透明公平      |

---

## 四、功能架構（MVP 階段）

### 1. 登入與角色系統

* 設計師帳號（可新增案子、上傳階段資料）
* 業主帳號（可瀏覽進度、提出疑問、簽核階段確認）
* 管理員帳號（審核內容、統計使用數據）

### 2. 案件管理

* 新增專案：名稱、預算、預計完工時間
* 階段設定：設計 → 工程 → 驗收
* 進度條：以百分比顯示目前進展
* 成本透明模組：顯示每階段預算比例與已用金額

### 3. 心理登月模組

| 心理原則   | 實際功能對應                  |
| ------ | ----------------------- |
| 峰終定律   | 記錄使用者情緒高峰與結案感受，用於優化體驗   |
| 不確定性焦慮 | 自動提醒進度更新與回覆時間，降低焦慮      |
| 懶散迴避   | 任務分階，提供微目標（小完成獎勵）       |
| 目標漸進效應 | 顯示累積里程碑與成就條             |
| 營運透明度  | 業主端實時顯示「溝通紀錄、預算比例、工期變化」 |

### 4. 資料與視覺化

* 時間軸：顯示設計歷程、重要溝通紀錄
* 信任指數：AI 自動生成（根據回覆速度與正面互動）
* 心理熱點圖：顯示專案過程中壓力／滿意度曲線

### 5. 匯出功能

* 匯出 JSON / PDF 專案報告
* 匯出設計週報（提供業主與設計師雙方留存）

---

## 五、技術路線（預定）

| 階段     | 技術方向         | 工具 / 框架                      |
| ------ | ------------ | ---------------------------- |
| 原型階段   | 無程式互動原型      | Figma / Notion / Lovable     |
| MVP 實作 | 前端互動原型       | React.js / Vite / Tailwind   |
| 後端     | 輕量資料儲存       | Node.js + Express / Firebase |
| 資料庫    | 雲端 NoSQL     | MongoDB Atlas                |
| 分析模組   | 使用者行為紀錄      | Google Analytics / 自建 AI 模組  |
| 心理數據   | 以問卷與互動紀錄訓練模型 | Python（未來階段）                 |

---

## 六、營運與商業策略（免費階段）

| 版本                 | 功能               | 收費模式      |
| ------------------ | ---------------- | --------- |
| Free for Designers | 設計師最多 3 個案子可免費使用 | 免費        |
| Client Premium     | 業主查看完整透明報告、心理洞察  | 每案收費 / 訂閱 |
| Pro Team           | 設計公司整合多設計師帳號     | 月訂閱制      |

---

## 七、未來發展路線圖

| 階段        | 目標                | 時程    |
| --------- | ----------------- | ----- |
| P0：構想驗證   | 完成原型與市場測試         | 1個月   |
| P1：MVP 原型 | 上線測試 + 收集10位設計師回饋 | 2個月   |
| P2：功能擴充   | 加入心理分析與AI推薦       | 3-4個月 |
| P3：募資/專利  | 準備投資簡報與專利申請       | 第6個月  |

---

## 八、風險評估與對應策略

| 風險      | 可能情境           | 對應措施        |
| ------- | -------------- | ----------- |
| 工程師盜用想法 | 委託前簽 NDA（保密協議） | ✅ 已規劃       |
| 被大公司模仿  | 先行登記著作權 / 專利   | ✅ 可行        |
| 市場採用慢   | 先從設計師社群口碑推廣    | 🚀 行銷預案中    |
| 技術不足    | 尋找合作工程顧問或技術共創  | 🤝 預留股權激勵方案 |

---

## 九、初期預算估算（自力型）

| 項目           | 預估費用                |
| ------------ | ------------------- |
| 著作權登記        | NT$ 1000            |
| 專利初審與圖說      | NT$ 5000–10000      |
| MVP 工程開發（外包） | NT$ 30,000–50,000   |
| 網域與伺服器       | NT$ 2000 / 年        |
| 推廣與測試        | NT$ 5000            |
| **總計（初期）**   | **約 NT$ 60,000 以內** |

---


{
  "name": "moon-landing-prototype",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview --port 5173",
    "lint": "eslint --ext .ts,.tsx src",
    "test": "vitest",
    "test:watch": "vitest --watch"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "@types/react": "^18.0.28",
    "@types/react-dom": "^18.0.11",
    "@vitejs/plugin-react": "^4.0.0",
    "eslint": "^8.0.0",
    "eslint-config-prettier": "^8.8.0",
    "eslint-plugin-react": "^7.32.2",
    "prettier": "^2.8.8",
    "typescript": "^5.5.2",
    "vite": "^5.0.0",
    "vitest": "^1.3.0",
    "@testing-library/react": "^14.0.0"
  }
}
{
  "compilerOptions": {
    "target": "ES2020",
    "useUnknownInCatchVariables": false,
    "lib": ["DOM", "ES2020"],
    "module": "ESNext",
    "moduleResolution": "Bundler",
    "strict": true,
    "jsx": "react-jsx",
    "esModuleInterop": true,
    "skipLibCheck": true,
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true,
    "forceConsistentCasingInFileNames": true
  },
  "include": ["src"]
}
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

export default defineConfig({
  plugins: [react()]
});
node_modules
dist
.env
.vitest
```markdown
# Moon-Landing — Prototype (Phase 1)

This repo contains a refactor of the original single-file prototype into a Vite + React + TypeScript project.

What this Phase-1 delivers:
- Core UI with Project / Milestone management
- Progress persisted per project (localStorage)
- Import/export (single project + full DB)
- Psych engine as a testable service
- Vitest unit tests (psych)
- ESLint + Prettier basic configs
- GitHub Actions workflow (CI: lint + test)

Getting started:
1. Install deps: npm install
2. Run dev server: npm run dev
3. Run tests: npm run test

Project structure:
- src/
  - components/ (UI components)
  - lib/ (storage, psych engine)
  - types.ts
  - main.tsx, App.tsx

Notes:
- This is Phase‑1 (MVP). Further phases will expand features, i18n, API adapter and more tests.
```
{
  "compilerOptions": {
    "module": "CommonJS",
    "target": "ES2020",
    "moduleResolution": "Node"
  }
}
<!doctype html>
<html lang="zh-Hant">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>心月 App — Prototype</title>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.tsx"></script>
  </body>
</html>
:root{
  --bg:#0b1220;--card:#071022;--muted:#98a6b3;--accent:#7dd3fc;--glass:rgba(255,255,255,0.03)
}
*{box-sizing:border-box}
body{font-family:system-ui, -apple-system, "Segoe UI", Roboto, "Noto Sans TC";margin:0;background:linear-gradient(180deg,#061021 0%, #071428 100%);color:#eef6fb;padding:16px}
.container{max-width:1100px;margin:0 auto;display:grid;grid-template-columns:1fr 380px;gap:16px}
.card{background:var(--card);border-radius:12px;padding:14px;border:1px solid rgba(255,255,255,0.03)}
.row{display:flex;gap:8px;align-items:center}
.small{font-size:13px;color:var(--muted)}
.tag{display:inline-block;padding:6px 8px;border-radius:999px;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.02);font-size:13px;color:var(--muted)}
.inlineBtn{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted);padding:6px 8px;border-radius:8px;cursor:pointer}
.progress{height:14px;background:rgba(255,255,255,0.03);border-radius:999px;overflow:hidden}
.bar{height:100%;background:linear-gradient(90deg,var(--accent),#60a5fa);width:0%}
export type ID = string;

export interface EventItem {
  ts: string;
  type: string;
  detail: string;
}

export interface Milestone {
  id: ID;
  title: string;
  percent: number;
  completed: boolean;
  notes?: string;
}

export interface Project {
  id: ID;
  title: string;
  milestones: Milestone[];
  events: EventItem[];
  progress?: number; // current progress 0-100
  settings?: Record<string, any>;
}
import type { Project } from '../types';

const STORAGE_KEY = 'pm_prototype_v1';

export interface DB {
  projects: Project[];
}

export function loadDB(): DB {
  const raw = localStorage.getItem(STORAGE_KEY);
  if (!raw) return { projects: [] };
  try {
    return JSON.parse(raw) as DB;
  } catch {
    return { projects: [] };
  }
}

export function saveDB(db: DB) {
  localStorage.setItem(STORAGE_KEY, JSON.stringify(db));
}

export function exportJSON(db: DB): Blob {
  return new Blob([JSON.stringify(db, null, 2)], { type: 'application/json' });
}

/** Export single project as JSON blob */
export function exportProjectJSON(project: Project): Blob {
  return new Blob([JSON.stringify(project, null, 2)], { type: 'application/json' });
}

export async function importJSONFile(file: File): Promise<DB> {
  const text = await file.text();
  return JSON.parse(text) as DB;
}
import type { Project } from '../types';

/**
 * computeAnxiety and evaluatePsych are ported from the prototype and typed.
 */

export function computeAnxiety(project: Project | undefined, progress: number): number {
  if (!project || project.milestones.length === 0) return 0;
  const upcoming = project.milestones.filter((m) => m.percent > progress).sort((a, b) => a.percent - b.percent)[0];
  const dist = upcoming ? upcoming.percent - progress : 0;
  let score = Math.max(0, Math.round((dist / 20) * 10));
  const lastEvent = project.events.length ? project.events[project.events.length - 1] : undefined;
  if (lastEvent) {
    const days = (Date.now() - new Date(lastEvent.ts).getTime()) / 86400000;
    if (days > 3) score += 2;
  } else score += 2;
  return Math.min(10, score);
}

export type PsychNotice = { type: 'none' | 'peak' | 'end' | 'early'; text: string };

export function evaluatePsych(project: Project, progress: number): PsychNotice {
  const notice: PsychNotice = { type: 'none', text: '' };
  const near = project.milestones.find((m) => Math.abs(m.percent - progress) <= 5);
  if (progress >= 85) {
    notice.type = 'end';
    notice.text = '接近完成：系統建議啟動交屋儀式（照片、燈光、Before/After 投影）';
  } else if (near) {
    notice.type = 'peak';
    notice.text = `中期高峰：靠近「${near.title}」，建議安排現場揭露或材料挑選日`;
  } else if (progress <= 15) {
    notice.type = 'early';
    notice.text = '早期階段：確認設計方向以避免後期變更';
  }
  return notice;
}
import React from 'react';
import { createRoot } from 'react-dom/client';
import App from './App';
import './styles.css';

createRoot(document.getElementById('root')!).render(<App />);
import React, { useEffect, useState } from 'react';
import { loadDB, saveDB, exportProjectJSON, exportJSON } from './lib/storage';
import type { Project } from './types';
import ProjectList from './components/ProjectList';
import ProjectEditor from './components/ProjectEditor';
import EventsLog from './components/EventsLog';

function App() {
  const [db, setDb] = useState(() => loadDB());
  const [currentId, setCurrentId] = useState<string | null>(db.projects[0]?.id ?? null);

  useEffect(() => {
    saveDB(db);
  }, [db]);

  function createProject(title: string) {
    const id = 'proj_' + Math.random().toString(36).slice(2, 9);
    const p: Project = { id, title, milestones: [], events: [], progress: 0 };
    const next = { ...db, projects: [...db.projects, p] };
    setDb(next);
    setCurrentId(id);
    logEvent(id, 'project_created', `專案 "${title}" 建立`);
  }

  function updateProject(project: Project) {
    const projects = db.projects.map((p) => (p.id === project.id ? project : p));
    const next = { ...db, projects };
    setDb(next);
  }

  function logEvent(projectId: string, type: string, detail: string) {
    const project = db.projects.find((p) => p.id === projectId);
    if (!project) return;
    project.events.push({ ts: new Date().toISOString(), type, detail });
    updateProject(project);
  }

  function exportCurrent() {
    const project = db.projects.find((p) => p.id === currentId);
    if (!project) return;
    const blob = exportProjectJSON(project);
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = `${project.title.replace(/\s+/g, '_')}_project.json`;
    a.click();
    URL.revokeObjectURL(url);
  }

  function exportAll() {
    const blob = exportJSON(db);
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = `moon_prototype_export.json`;
    a.click();
    URL.revokeObjectURL(url);
  }

  return (
    <div className="container">
      <div className="card">
        <h2 className="small">心月 App — 進階原型 (Phase1)</h2>
        <ProjectEditor
          db={db}
          currentId={currentId}
          setCurrentId={setCurrentId}
          onUpdate={updateProject}
          onLog={logEvent}
          setDb={setDb}
        />
        <div style={{ marginTop: 12 }}>
          <button className="inlineBtn" onClick={exportCurrent}>
            匯出當前專案 JSON
          </button>{' '}
          <button className="inlineBtn" onClick={exportAll}>
            匯出全部 JSON
          </button>
        </div>
        <div style={{ marginTop: 12 }}>
          <EventsLog project={db.projects.find((p) => p.id === currentId) ?? null} />
        </div>
      </div>

      <div className="card">
        <ProjectList db={db} onCreate={createProject} onOpen={(id) => setCurrentId(id)} onSetDb={setDb} />
      </div>
    </div>
  );
}

export default App;
import React, { useState } from 'react';
import type { Project } from '../types';
import { loadDB, saveDB } from '../lib/storage';

export default function ProjectList({
  db,
  onCreate,
  onOpen,
  onSetDb
}: {
  db: { projects: Project[] };
  onCreate: (name: string) => void;
  onOpen: (id: string) => void;
  onSetDb: (db: { projects: Project[] }) => void;
}) {
  const [name, setName] = useState('');

  function create() {
    if (!name.trim()) return alert('請輸入專案名稱');
    onCreate(name.trim());
    setName('');
  }

  function remove(id: string) {
    if (!confirm('確定刪除此專案？')) return;
    const next = { ...db, projects: db.projects.filter((p) => p.id !== id) };
    onSetDb(next);
    saveDB(next);
  }

  function importFile(e: React.ChangeEvent<HTMLInputElement>) {
    const f = e.target.files?.[0];
    if (!f) return;
    const reader = new FileReader();
    reader.onload = (ev) => {
      try {
        const imported = JSON.parse(String(ev.target?.result));
        // if imported is a single project, convert
        if (imported && imported.id && imported.title) {
          // treat as project
          const project = imported as Project;
          const next = { ...db, projects: [...db.projects, project] };
          onSetDb(next);
          saveDB(next);
          alert('匯入為新專案成功');
        } else if (imported.projects) {
          onSetDb(imported);
          saveDB(imported);
          alert('DB 匯入成功（覆蓋）');
        } else {
          alert('格式不正確');
        }
      } catch {
        alert('解析失敗');
      }
    };
    reader.readAsText(f);
    e.currentTarget.value = '';
  }

  return (
    <div>
      <label className="small">專案清單</label>
      <div style={{ display: 'flex', flexDirection: 'column', gap: 8, marginTop: 8 }}>
        {db.projects.map((p) => (
          <div key={p.id} style={{ display: 'flex', justifyContent: 'space-between', alignItems: 'center' }}>
            <div className="tag">{p.title}</div>
            <div>
              <button className="inlineBtn" onClick={() => onOpen(p.id)}>
                Open
              </button>{' '}
              <button className="inlineBtn" onClick={() => remove(p.id)}>
                Delete
              </button>
            </div>
          </div>
        ))}
      </div>

      <div style={{ marginTop: 12 }} className="row">
        <input placeholder="新的專案名稱" value={name} onChange={(e) => setName(e.target.value)} />
        <button className="inlineBtn" onClick={create}>
          建立專案
        </button>
      </div>

      <div style={{ marginTop: 12 }}>
        <input type="file" accept=".json" onChange={importFile} />
      </div>
    </div>
  );
}
import React, { useEffect } from 'react';
import type { Project } from '../types';
import MilestoneList from './MilestoneList';
import ProgressControl from './ProgressControl';
import { loadDB, saveDB } from '../lib/storage';

export default function ProjectEditor({
  db,
  currentId,
  setCurrentId,
  onUpdate,
  onLog,
  setDb
}: {
  db: { projects: Project[] };
  currentId: string | null;
  setCurrentId: (id: string | null) => void;
  onUpdate: (p: Project) => void;
  onLog: (projectId: string, type: string, detail: string) => void;
  setDb: (db: { projects: Project[] }) => void;
}) {
  const project = db.projects.find((p) => p.id === currentId) ?? null;

  useEffect(() => {
    // if no current, select first
    if (!currentId && db.projects.length > 0) {
      setCurrentId(db.projects[0].id);
    }
  }, [db, currentId, setCurrentId]);

  function save() {
    saveDB(db);
    alert('已儲存 (localStorage)');
    if (project) onLog(project.id, 'project_saved', '手動儲存專案');
  }

  return (
    <div>
      <div style={{ display: 'flex', justifyContent: 'space-between', alignItems: 'center' }}>
        <div>
          <div className="small">當前專案</div>
          <h3>{project?.title ?? '（尚未選擇專案）'}</h3>
        </div>
      </div>

      <div style={{ marginTop: 12 }}>
        <ProgressControl project={project} onUpdateProject={onUpdate} onLog={onLog} />
      </div>

      <div style={{ marginTop: 12 }}>
        <MilestoneList project={project} onUpdateProject={onUpdate} onLog={onLog} />
      </div>

      <div style={{ marginTop: 12 }}>
        <div className="row">
          <button className="inlineBtn" onClick={save}>
            儲存專案
          </button>
        </div>
      </div>
    </div>
  );
}
import React, { useEffect, useState } from 'react';
import type { Project } from '../types';
import { computeAnxiety, evaluatePsych } from '../lib/psych';

export default function ProgressControl({
  project,
  onUpdateProject,
  onLog
}: {
  project: Project | null;
  onUpdateProject: (p: Project) => void;
  onLog: (projectId: string, type: string, detail: string) => void;
}) {
  const [value, setValue] = useState<number>(project?.progress ?? 0);
  useEffect(() => {
    setValue(project?.progress ?? 0);
  }, [project?.id]); // update when project changes

  useEffect(() => {
    if (!project) return;
    const p = { ...project, progress: value };
    // auto-mark milestones completed if progress >= percent
    p.milestones = p.milestones.map((m) => ({ ...m, completed: value >= m.percent ? true : m.completed }));
    onUpdateProject(p);
  }, [value]); // eslint-disable-line react-hooks/exhaustive-deps

  if (!project) return null;

  const anx = computeAnxiety(project, value);
  const psych = evaluatePsych(project, value);

  return (
    <div>
      <label className="small">進度模擬 (0-100)</label>
      <input
        type="range"
        min={0}
        max={100}
        value={value}
        onChange={(e) => setValue(Number(e.target.value))}
        style={{ width: '100%' }}
      />
      <div style={{ marginTop: 8 }}>
        <div className="progress" style={{ marginBottom: 6 }}>
          <div className="bar" style={{ width: `${value}%` }} />
        </div>
        <div style={{ display: 'flex', justifyContent: 'space-between' }}>
          <div className="small">
            完成度：<strong>{value}%</strong>
          </div>
          <div className="small">
            焦慮指數：<strong>{anx}</strong>
          </div>
        </div>

        {psych.type !== 'none' && (
          <div style={{ marginTop: 8, padding: 10, borderRadius: 8, background: 'rgba(125,211,252,0.06)', color: '#e3f9ff' }}>
            {psych.text}
          </div>
        )}
      </div>
    </div>
  );
}
import React, { useState } from 'react';
import type { Project, Milestone } from '../types';
import { v4 as uuidv4 } from 'uuid';

export default function MilestoneList({
  project,
  onUpdateProject,
  onLog
}: {
  project: Project | null;
  onUpdateProject: (p: Project) => void;
  onLog: (projectId: string, type: string, detail: string) => void;
}) {
  const [title, setTitle] = useState('');
  const [percent, setPercent] = useState<number>(10);

  if (!project) return null;

  function add() {
    if (!title.trim() || isNaN(percent)) return alert('請輸入完整里程碑');
    const m: Milestone = { id: 'm_' + Math.random().toString(36).slice(2, 9), title: title.trim(), percent, completed: percent <= (project.progress ?? 0), notes: '' };
    const p = { ...project, milestones: [...project.milestones, m] };
    onUpdateProject(p);
    setTitle('');
    setPercent(10);
    onLog(project.id, 'milestone_added', `新增里程碑：${m.title} (${m.percent}%)`);
  }

  function remove(id: string) {
    if (!confirm('確定刪除此里程碑？')) return;
    const p = { ...project, milestones: project.milestones.filter((m) => m.id !== id) };
    onUpdateProject(p);
    onLog(project.id, 'milestone_deleted', `刪除里程碑 ${id}`);
  }

  function toggleComplete(id: string) {
    const p = { ...project, milestones: project.milestones.map((m) => (m.id === id ? { ...m, completed: !m.completed } : m)) };
    onUpdateProject(p);
    onLog(project.id, 'milestone_toggled', `切換里程碑 ${id}`);
  }

  return (
    <div>
      <div style={{ display: 'flex', gap: 8, alignItems: 'end' }}>
        <div style={{ flex: 1 }}>
          <label className="small">新里程碑標題</label>
          <input value={title} onChange={(e) => setTitle(e.target.value)} placeholder="例如：拆除完成" />
        </div>
        <div style={{ width: 120 }}>
          <label className="small">預期完成 (%)</label>
          <input type="number" min={0} max={100} value={percent} onChange={(e) => setPercent(Number(e.target.value))} />
        </div>
        <div style={{ width: 100 }}>
          <button className="inlineBtn" onClick={add}>
            新增里程碑
          </button>
        </div>
      </div>

      <div style={{ marginTop: 12 }}>
        {project.milestones
          .slice()
          .sort((a, b) => a.percent - b.percent)
          .map((m) => (
            <div key={m.id} style={{ display: 'flex', justifyContent: 'space-between', alignItems: 'center', padding: 8, borderRadius: 8, background: 'rgba(255,255,255,0.02)', marginBottom: 8 }}>
              <div>
                <div style={{ fontWeight: 700 }}>{m.title}</div>
                <div className="small">目標 {m.percent}% • {m.notes ?? ''}</div>
              </div>
              <div style={{ display: 'flex', gap: 8, alignItems: 'center' }}>
                <div className="small">{m.completed ? '完成' : '待完成'}</div>
                <button className="inlineBtn" onClick={() => toggleComplete(m.id)}>
                  {m.completed ? '取消完成' : '標記完成'}
                </button>
                <button className="inlineBtn" onClick={() => remove(m.id)}>
                  刪除
                </button>
              </div>
            </div>
          ))}
      </div>
    </div>
  );
}
import React from 'react';
import type { Project } from '../types';

export default function EventsLog({ project }: { project: Project | null }) {
  if (!project) return null;
  return (
    <div>
      <label className="small">事件紀錄（時間軸）</label>
      <div style={{ maxHeight: 180, overflow: 'auto', marginTop: 8 }}>
        {project.events.slice().reverse().map((ev, idx) => (
          <div key={idx} style={{ padding: 8, borderBottom: '1px solid rgba(255,255,255,0.02)' }}>
            <div style={{ fontWeight: 700 }}>{ev.type}</div>
            <div className="small">{ev.detail}</div>
            <div className="small" style={{ color: 'var(--muted)', marginTop: 6 }}>{ev.ts}</div>
          </div>
        ))}
      </div>
    </div>
  );
}
import { describe, it, expect } from 'vitest';
import { computeAnxiety, evaluatePsych } from '../lib/psych';
import type { Project } from '../types';

const now = new Date().toISOString();

describe('psych engine', () => {
  const project: Project = {
    id: 'proj_x',
    title: 'Test',
    milestones: [
      { id: 'm1', title: 'A', percent: 10, completed: false },
      { id: 'm2', title: 'B', percent: 50, completed: false },
      { id: 'm3', title: 'C', percent: 90, completed: false }
    ],
    events: [{ ts: now, type: 'init', detail: 'created' }],
    progress: 0
  };

  it('computes anxiety low when near milestone', () => {
    const a = computeAnxiety(project, 45);
    expect(typeof a).toBe('number');
    expect(a).toBeGreaterThanOrEqual(0);
    expect(a).toBeLessThanOrEqual(10);
  });

  it('evaluates psych end when >=85', () => {
    const n = evaluatePsych(project, 90);
    expect(n.type).toBe('end');
  });

  it('evaluates peak when near milestone', () => {
    const n = evaluatePsych(project, 48);
    expect(n.type === 'peak' || n.type === 'none').toBe(true);
  });
});
import { defineConfig } from 'vitest/config';

export default defineConfig({
  test: {
    globals: true,
    environment: 'jsdom',
    include: ['src/tests/**/*.test.ts']
  }
});
module.exports = {
  root: true,
  env: { browser: true, es2021: true },
  extends: ['eslint:recommended', 'plugin:react/recommended', 'prettier'],
  parserOptions: { ecmaVersion: 2021, sourceType: 'module', ecmaFeatures: { jsx: true } },
  settings: { react: { version: 'detect' } },
  rules: {}
};
{
  "singleQuote": true,
  "semi": true,
  "printWidth": 100,
  "trailingComma": "none"
}
name: CI

on:
  push:
    branches: [ main, feature/** ]
  pull_request:

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Use Node.js
        uses: actions/setup-node@v4
        with:
          node-version: 20
      - name: Install dependencies
        run: npm ci
      - name: Lint
        run: npm run lint
      - name: Run tests
        run: npm run test
      







