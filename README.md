<!-- Hero: 带渐变背景与轻量动画的 SVG 横幅 -->
<div align="center">
  <svg viewBox="0 0 1200 280" width="100%" height="180" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" style="border-radius:12px;overflow:hidden;">
    <defs>
      <linearGradient id="g1" x1="0%" x2="100%" y1="0%" y2="100%">
        <stop offset="0%" stop-color="#0f172a"/>
        <stop offset="50%" stop-color="#0ea5a4"/>
        <stop offset="100%" stop-color="#7c3aed"/>
      </linearGradient>
      <filter id="f1" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="24" result="blur" />
        <feBlend in="SourceGraphic" in2="blur" mode="screen" />
      </filter>
    </defs>

    <rect width="1200" height="280" fill="url(#g1)" />

    <!-- 背景漂浮圆点，使用 SMIL 动画 -->
    <g fill-opacity="0.12" filter="url(#f1)">
      <circle cx="120" cy="60" r="40" fill="#ffffff">
        <animate attributeName="cx" dur="12s" values="120;1100;120" repeatCount="indefinite" />
        <animate attributeName="cy" dur="8s" values="60;200;60" repeatCount="indefinite" />
      </circle>
      <circle cx="400" cy="40" r="28" fill="#ffffff">
        <animate attributeName="cx" dur="10s" values="400;900;400" repeatCount="indefinite" />
        <animate attributeName="cy" dur="14s" values="40;150;40" repeatCount="indefinite" />
      </circle>
      <circle cx="900" cy="160" r="60" fill="#ffffff">
        <animate attributeName="cx" dur="16s" values="900;200;900" repeatCount="indefinite" />
        <animate attributeName="cy" dur="9s" values="160;40;160" repeatCount="indefinite" />
      </circle>
    </g>

    <!-- 标题文本 -->
    <g fill="#fff" font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif">
      <text x="60" y="110" font-size="40" font-weight="700">Yak0xff</text>
      <text x="60" y="150" font-size="16" fill="#e6f6f5">移动应用工程师 · 专注产品体验与工程实现</text>

      <!-- CTA 样式下划线动效 -->
      <g transform="translate(60,168)">
        <rect x="0" y="10" width="220" height="2" fill="#ffffff" opacity="0.07" rx="1" />
        <rect x="0" y="10" width="0" height="2" fill="#fff">
          <animate attributeName="width" dur="2.6s" values="0;220;0" repeatCount="indefinite" />
        </rect>
      </g>
    </g>
  </svg>
</div>


# Yak0xff

<div align="center">
  <sub style="color:#94a3b8">简洁 · 专注 · 实用 · 有温度的工程</sub>
</div>

---

<!-- 横向徽章：使用内联 SVG 图标增强质感 -->
<p align="center">
  <svg width="16" height="16" viewBox="0 0 24 24" style="vertical-align:middle;margin-right:6px" xmlns="http://www.w3.org/2000/svg">
    <circle cx="12" cy="12" r="10" fill="#0ea5a4" />
  </svg>
  <strong>移动端 · 产品体验 · 工程化</strong>
</p>

---

## 关于我

移动开发工程师，专注于用简洁的设计与稳健的工程实现高质量的移动体验。我在意细节与流畅的交互，擅长把复杂需求拆解为可交付的模块，追求长期可维护的架构。

---

## 设计亮点（可视化）

<div>
  <!-- 小卡片：带轻微 hover 提示的静态效果（在 README 中为视觉参考） -->
  <svg width="100%" height="60" viewBox="0 0 900 60" xmlns="http://www.w3.org/2000/svg">
    <rect x="0" y="0" rx="8" width="900" height="60" fill="rgba(255,255,255,0.04)" />
    <text x="20" y="36" fill="#fff" font-size="14" font-family="Segoe UI, Roboto">以用户路径为核心 · 模块化组件 · 关键路径优先优化</text>
  </svg>
</div>

---

## 技术栈（精选）

- 语言：Objective‑C / Swift / Dart / TypeScript / JavaScript / Python
- 框架：Flutter / React Native / SwiftUI / Jetpack Compose
- 工具：Android Studio / Xcode / Firebase / Git / GitHub Actions
- 擅长：UI/UX、性能优化、架构设计、离线与网络同步、产品化落地

---

## 代表项目（卡片式简述）

- Movie Tracker — 观影记录与推荐（注重流畅动画与离线缓存）
- Sports Scoreboard — 实时比分与通知（优先考虑推送稳定性与低延迟）

---

## 近期学习

- Flutter / SwiftUI 高级动效与微交互
- 在移动端集成轻量级 AI/ML（推荐与个性化）
- 提升工程化：测试覆盖、CI/CD 流程、可观测性

---

## 联系方式

- GitHub: https://github.com/Yak0xff
- Email: （若需加入邮箱请告知）

---

<footer>
<p align="center" style="color:#94a3b8">简约而精致 · 用更少的界面，传达更多有价值的信息。</p>
</footer>
