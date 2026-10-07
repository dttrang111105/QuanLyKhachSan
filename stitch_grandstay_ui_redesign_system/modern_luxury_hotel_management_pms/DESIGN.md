---
name: Modern Luxury Hotel Management PMS
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#725b38'
  on-secondary: '#ffffff'
  secondary-container: '#fedeb2'
  on-secondary-container: '#78603e'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001a42'
  on-tertiary-container: '#3980f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#fedeb2'
  secondary-fixed-dim: '#e0c298'
  on-secondary-fixed: '#281800'
  on-secondary-fixed-variant: '#584323'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  title-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system serves a modern luxury hotel management platform and property management system (PMS). It synthesizes high-end European boutique hotel elegance with the high-throughput utility required by front desk staff, revenue managers, and executive hoteliers.

The visual style blends **Corporate Modern** structure with **Editorial Luxury Minimalism**:
- **Poise & Authority:** Dominated by deep midnight navy tones, conveying absolute security, prestige, and institutional permanence.
- **Tailored Warmth:** Accentuated by soft champagne gold and warm ochre highlights, evoking bespoke hospitality, concierge precision, and understated wealth rather than gaudy opulence.
- **Tactile Clarity:** Interfaces rely on ultra-crisp white surfaces framed by hairline slate borders, generous spacing, and calm ambient depth. Visual friction is minimized so that high-stress administrative tasks—such as walk-in check-ins, VIP room allocation, and occupancy forecasting—feel effortless, controlled, and premium.

## Colors

The palette establishes an ultra-clean, daylight-first interface balanced with authoritative deep tones and tactile status indicators:

- **Primary Canvas & Surfaces:** Background foundation is fixed on Crisp Slate (`#F8FAFC`), transitioning to pure white (`#FFFFFF`) for structural cards, data sheets, and modal panels. Structural dividers and borders utilize delicate slate tones (`#E2E8F0`).
- **Brand Core:** Primary actions, sidebar canvases, and active navigations leverage Deep Midnight Slate (`#0F172A` / `#0B192C`).
- **Luxury Accent:** Champagne Gold (`#C5A880`) and Warm Ochre (`#B48B57`) provide contextual hierarchy—highlighting VIP designations, guest loyalty tiers, active tab underlines, and key financial summaries.
- **Operational Status Palette:**
  - *Available / Operational Success:* Emerald Green (`#10B981` surface, `#059669` text/border).
  - *Occupied / Critical / Urgent:* Crisp Crimson (`#EF4444` surface, `#B91C1C` text).
  - *Maintenance / Pending / Audit:* Warm Amber (`#F59E0B` surface, `#B45309` text).
  - *Cleaning / In Turnover / Reserved:* Slate Indigo & Sky (`#3B82F6` / `#6366F1`).

## Typography

The typography strategy leverages **Plus Jakarta Sans** across all levels, chosen for its contemporary geometric balance, subtle warmth, and clear legibility at compact data scales.

- **KPI Numbers & Financials:** Display numbers (`display-lg` and `headline-lg`) must use tabular figures (`font-variant-numeric: tabular-nums`) to maintain alignment during real-time updates and rate adjustments.
- **Editorial Subtlety:** Section titles (`16px`) use medium-to-semibold weights with tightened letter tracking (`-0.005em`) to retain a luxury print feel.
- **Dense Operational Interfaces:** Data tables and guest folios rely primarily on `13px` (`body-sm`) and `14px` (`body-md`) with calibrated line heights to prevent visual crowding across wide viewports.
- **Status Badges & Identifiers:** Room status badges and category pills utilize `11px` (`caption`) and `12px` (`label-sm`) with uppercase transformation and slight letter spacing (`0.02em` to `0.04em`) to maintain legibility against colored tint backgrounds.

## Layout & Spacing

The layout architecture implements a high-utility administrative workspace built on an adaptive multi-tier layout structure:

- **Desktop Structure (min-width: 1280px):**
  - **Categorized Left Navigation:** Fixed-width 260px collapsible sidebar (collapsible to an 80px micro-icon bar) housing operational categories (*Dashboard, Quản lý phòng & đặt phòng, Báo cáo & Doanh thu, Cấu hình hệ thống*).
  - **Global Utility Topbar:** 64px fixed-height header containing dynamic breadcrumbs, high-affinity global search (filtering rooms, guests, booking references), instant alert notifications, and an administrative profile menu.
  - **Work Surface:** 12-column fluid grid system with `1.5rem` (24px) gutters and `2rem` (32px) margins, preventing horizontal cramping during 100% full-screen room occupancy matrix views.
- **Tablet / Responsive Desk (768px – 1279px):**
  - Sidebar automatically collapses to an off-canvas drawer or 72px icon column.
  - Gutters decrease to `1rem` (16px); KPI metric grids wrap from 4 columns to 2x2 formations.
- **Mobile Handheld (under 768px):**
  - Sidebar transitions to a slide-over sheet controlled via the top bar hamburger trigger.
  - Outer page margins reduce to `1rem` (16px), gutters scale to `0.75rem` (12px), and tables activate horizontal scroll envelopes with fixed status columns.

## Elevation & Depth

Visual depth is expressed through subtle ambient diffusion and layered surfaces rather than aggressive, high-contrast drop shadows:

- **Surface Ground (`Level 0`):** `#F8FAFC` base application canvas. Zero elevation.
- **Resting Panels & Cards (`Level 1`):** Pure white cards (`#FFFFFF`) with a 1px border (`#E2E8F0`) paired with an ultra-soft ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`.
- **Interactive Hover & Elevated States (`Level 2`):** Room grid cards on hover, quick-action tiles, and dropdown trigger states: `0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Floating Overlays & Popovers (`Level 3`):** Room detail quick-peek flyouts, calendar day pickers, and global filter drawers: `0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.03)`.
- **System Modals & Check-in Drawers (`Level 4`):** Check-in/Folio walk-through modals: `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.04)` over a backdrop blur overlay (`rgba(15, 23, 42, 0.4)` with `backdrop-filter: blur(4px)`).

## Shapes

The design system implements a refined curvature scale to balance professional software discipline with hospitality sophistication:

- **Structural Containers (Cards, Modals, Drawers):** Built with `12px` to `14px` border radius (`rounded-xl`), creating calm, approachable frames that soften high-density tabular data.
- **Controls & Form Elements (Inputs, Selects, Buttons):** Standardized on `10px` (`rounded-lg`) to balance spatial density with tactile touch zones.
- **Status Pills, Room Indicators & Tags:** Strict `6px` radius (`rounded-md`), establishing an intentional visual distinction between actionable controls and informative tags.
- **System Avatars & Fast Actions:** Full circular geometry (`rounded-full`) for VIP guest avatars and notification dot indicators.

## Components

### Buttons
- **Primary:** Deep Navy background (`#0F172A`), white label (`#FFFFFF`), `10px` radius, height `40px` (standard) or `34px` (dense table context). Hover state darkens to `#0B192C` with subtle `shadow-sm`.
- **Accent / VIP Action:** Subtle Champagne Gold fill (`#C5A880`), text `#FFFFFF`, transition to `#B48B57` on hover. Used for booking confirmations, VIP check-ins, and checkout reconciliation.
- **Secondary / Outline:** White background with 1px border (`#E2E8F0`), text `#0F172A`. On hover, background shifts to `#F1F5F9`.
- **Ghost:** Borderless, text `#64748B`, turning to `#0F172A` with `#F8FAFC` background on hover.

### Inputs & Filters
- **Text Inputs & Dropdowns:** 40px height, 1px border (`#E2E8F0`), background `#FFFFFF`, text `#0F172A`, placeholder `#94A3B8`. Focused state: border `#C5A880` with a 2px outer ring in `rgba(197, 168, 128, 0.2)`.
- **Search Bars:** Left-aligned magnifying icon (`#94A3B8`), subtle inset background (`#F8FAFC`), crisp border on focus.

### Status Badges & Pills
- Built with `6px` radius, `11px` or `12px` typography, `padding: 2px 8px`, semi-bold weight:
  - *Available:* Background `#ECFDF5`, text `#065F46`, border `1px solid #A7F3D0`.
  - *Occupied:* Background `#FEF2F2`, text `#991B1B`, border `1px solid #FECACA`.
  - *Maintenance:* Background `#FFFBEB`, text `#92400E`, border `1px solid #FDE68A`.
  - *Cleaning / Turnover:* Background `#EFF6FF`, text `#1E40AF`, border `1px solid #BFDBFE`.

### Data Tables
- **Container:** Pure white card framing with sticky header row (`#F8FAFC`), height `48px`.
- **Rows:** Minimum height `56px`, bottom border `1px solid #F1F5F9`. Hover state transitions background smoothly to `#F8FAFC`.
- **Action Triggers:** Inline, compact icon-button sets (View, Edit, More) right-aligned for consistent scanning.

### Metric KPI Cards
- **Structure:** White card container with 1px border (`#E2E8F0`), `1.25rem` padding.
- **Content Flow:** Upper row displays category label (`12px`, uppercase, `#64748B`) and a soft-tinted icon container (40x40px, rounded-lg). Middle row presents the metric value (`display-lg`, `#0F172A`). Bottom row shows trend indicators: Green pill for upward booking pace (`+14.2% vs last week`), Red for cancellations.

### Razor View (.cshtml) Integration Principles
- Markup structures should rely on clean semantic wrappers (`<article class="pms-card">`, `<div class="pms-table-responsive">`) ensuring zero collision with ASP.NET Core Tag Helpers (`asp-for`, `asp-action`, `asp-controller`).
- Dynamic status classes should leverage predictable state suffixes (`badge--available`, `badge--occupied`, `badge--cleaning`) for server-side Razor view evaluation.