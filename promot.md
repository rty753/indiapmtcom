<role> You are an expert frontend engineer, UI/UX designer, and visual branding specialist. Your goal is to replicate the "Modern Playful Tech" aesthetic of the Brainfish landing page. You prioritize high-fidelity visual reproduction, clean component architecture, and a cohesive user experience that feels both professional and whimsical. Before writing code, analyze the provided design system:

Identify the tech stack: Next.js, Tailwind CSS, Lucide React, and Framer Motion for animations.

Focus on the unique "Underwater/Sea" theme combined with "Bento Box" layouts.

Replicate the specific use of vibrant gradients, soft rounded corners, and illustrative accents.

Ensure the interface remains accessible (WCAG compliant) while maintaining its playful character. </role>

<design-system>

Design Philosophy
The "Brainfish" style is "Oceanic Intellectualism". It combines a clean, modern SaaS aesthetic with a playful, illustrative underwater theme. It balances professional reliability with creative accessibility through bright colors, fluid shapes, and high-quality custom icons.

Core Principles:

The "Bento" Grid: Content is organized into distinct, rounded containers with varying sizes, creating a clean but non-linear information hierarchy.

Fluid Gradients: Use of soft, vertical, and radial gradients that mimic the transition of light through water (from bright surface teals to deep ocean blues).

Marine Accents: Subtle use of coral, seaweed, and fish motifs that serve as functional UI decorations rather than just "clipart."

High-Contrast Clarity: Despite the playful colors, typography remains sharp and legible with high contrast against container backgrounds.

Floating Interactive Elements: Buttons and cards should feel buoyant, using subtle shadows and lift-on-hover effects.

Design Token System
Colors (Oceanic Palette)
Primary (Sea Foam): #A3E635 (Vibrant Lime Green) - Used for primary CTAs and key highlights.

Background (Surface): #F0FDF4 (Very light mint) transitioning to #3B82F6 (Electric Blue) and deep #1E3A8A (Deep Sea).

Containers: #FFFFFF (Pure White) with low-opacity borders or #F8FAFC (Ghost White).

Text: #0F172A (Deep Navy) for headings; #334155 (Slate) for body text.

Accents:

Coral Pink: #FDA4AF

Tropical Teal: #2DD4BF

Sunset Orange: #FB923C

Typography
Headings: Modern Geometric Sans (e.g., Plus Jakarta Sans or Inter). Bold weights (700-800) with tight letter spacing for a "chunky" professional look.

Body: Clean Sans-Serif (Inter or Geist). Regular weight (400-500) with generous line height (1.6) for readability.

Labels: All-caps with tracking (letter-spacing) for small metadata or section tags.

Radius & Border
Large Rounded Corners: Use rounded-2xl (16px) or rounded-3xl (24px) for all main containers and Bento cards.

Subtle Borders: border-[1px] border-slate-200/60.

Pill Shapes: Used for tags, small buttons, and navigation bars.

Shadows & Depth
Soft Glow: Instead of heavy black shadows, use colored glows or very soft shadow-xl with low opacity (e.g., shadow-blue-500/10).

Inner Gloss: Subtle top-border highlights to give containers a slightly "glassy" or "3D" feel.

Component Stylings
Navigation
Floating Bar: A centered, pill-shaped navbar with a backdrop blur (backdrop-blur-md) and a subtle border.

Hover: Links should have a subtle color shift or a small under-dot.

Buttons (The "Brainfish" CTA)
Primary: Solid Lime Green (#A3E635), black text, rounded-lg, bold font.

Hover Effect: Scales up slightly (scale-105) with a stronger glow.

Secondary: Ghost buttons with a thick border or light blue background.

Bento Cards
Structure: Each card has a specific "feature" focus. Use a mix of col-span and row-span in a CSS Grid.

Visuals: Top-aligned icons or illustrative SVG graphics. Bottom-aligned text with bold titles.

Interaction: Slight "tilt" or "lift" effect using Framer Motion on hover.

Feature Labels
Small, rounded tags with icons (e.g., a "Knowledge" tag with a light bulb icon) using pastel background colors that match the icon's theme.

Layout Strategy
Hero Section: Centered typography with a wide "Bento" visual below it. Use a massive, soft radial gradient as the background centerpiece.

The "Flow": Use wavy section dividers or overlapping SVG shapes to transition between light and dark sections, mimicking ocean waves.

Whitespace: Highly generous. Let the components "breathe" to avoid a cluttered SaaS look.

Non-Genericness (Bold Choices)
Animated SVG Paths: Use dashed lines or "bubbles" that move subtly in the background.

Custom Iconography: Icons should be thick-stroked and multi-colored, not thin line-art.

The "Fish" Logo: The logo is a simple, bold silhouette. Replicate this "chunky" geometric style in all decorative graphics.

</design-system>
1. 基本信息

网站名称：印度支付-最全支付资讯-专业一站式支付服务
域名：indiapmt.com
主题色：深蓝/暗黑 + 绿色（#2ECC71）
风格：现代、专业、B2B服务类


2. 页面结构
导航菜单（Header）

首页
关于
产品
博客
联系
CTA按钮：立即体验

主要内容版块（从上到下）
① 英雄区（Hero Section）

背景：湖水山景/自然风景大图
标题：欢迎 → 全方位支付服务平台
CTA按钮：立即体验（绿色）

② 关于我们区块

标题：关于印度支付的专业团队
内容：3列介绍专业性
右侧配图：日出风景图
CTA：阅读更多（链接到about页）

③ 核心价值观区块（3列）

01 全面服务 - 个性化支付解决方案
02 行业资讯 - 市场趋势信息
03 安全可靠 - 交易安全保障

④ 行动号召区块

背景：森林风景图 + 黑色透明覆盖
标题：立即加入我们，获取最佳服务
CTA：立即体验（绿色按钮）

⑤ 为什么选择我们区块

副标题：我们独特的价值主张
3个特性（2列布局）：

快速处理
多样化选择
专业支持



⑥ 客户反馈区块

3个推荐卡片，展示客户名字和评价
客户名单：李伟、王芳、陈莉
使用引号符号突出

⑦ 结束行动号召区块

背景：海滩/日落风景 + 黑色透明覆盖
标题：立即注册，开启便捷支付
CTA：立即体验

⑧ 页脚（Footer）

版权信息：版权 © 2026 印度支付-最全支付资讯-专业一站式支付服务


3. 设计特点
配色方案：

主色：深蓝/暗黑（背景）
强调色：绿色 #2ECC71（所有按钮和链接）
辅助：白色、淡灰蓝色（背景）
文本：白色、深灰

背景图片风格：

湖水+山景（宁静专业）
日出（希望/新开始）
森林（专业/稳重）
海滩日落（信任/舒适）
都采用黑色透明覆盖层

排版布局：

大标题 + 小标题（两层级）
3列网格布局（最常用）
左文右图或左图右文的交替布局
充足的白间距
响应式设计

交互元素：

绿色按钮（立即体验）重复出现多次
所有重要CTA按钮设计统一
内链导航（阅读更多）


4. 文案要素
核心价值主张：

全面服务：个性化解决方案
行业资讯：市场趋势信息
安全可靠：严格安全测试
快速处理：迅速处理交易
多样化选择：灵活支付方式
专业支持：及时技术支持

调性：

专业、可信、高效
强调安全和快速
着重客户满意度


**5. 建议（复制此网站时）
✅ 必须元素：

自然风景大图背景（专业感）
3-4个核心服务特性
客户推荐区块（社交证明）
多个CTA按钮（增加转化）
清晰的价值主张
简洁导航

✅ 推荐技术：

响应式设计
平滑滚动
浮动回到顶部按钮
绿色为主要行动色
深色背景搭配大图