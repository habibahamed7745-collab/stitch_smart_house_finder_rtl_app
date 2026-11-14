---
name: Smart House Finder
colors:
  surface: '#f8f9ff'
  surface-dim: '#d5dae6'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e9eefa'
  surface-container-high: '#e3e8f5'
  surface-container-highest: '#dde3ef'
  on-surface: '#161c25'
  on-surface-variant: '#44474c'
  inverse-surface: '#2b313a'
  inverse-on-surface: '#ebf1fd'
  outline: '#75777c'
  outline-variant: '#c4c6cc'
  surface-tint: '#535f6f'
  primary: '#091523'
  on-primary: '#ffffff'
  primary-container: '#1e2a38'
  on-primary-container: '#8591a2'
  inverse-primary: '#bbc7da'
  secondary: '#006a60'
  on-secondary: '#ffffff'
  secondary-container: '#8cf5e4'
  on-secondary-container: '#007166'
  tertiary: '#1f1202'
  on-tertiary: '#ffffff'
  tertiary-container: '#362611'
  on-tertiary-container: '#a48c70'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e3f6'
  primary-fixed-dim: '#bbc7da'
  on-primary-fixed: '#101c2a'
  on-primary-fixed-variant: '#3c4857'
  secondary-fixed: '#8cf5e4'
  secondary-fixed-dim: '#6fd8c8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#fbdebe'
  tertiary-fixed-dim: '#ddc2a3'
  on-tertiary-fixed: '#271905'
  on-tertiary-fixed-variant: '#56432c'
  background: '#f8f9ff'
  on-background: '#161c25'
  surface-variant: '#dde3ef'
typography:
  display-brand:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Be Vietnam Pro
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  price-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
  spec-numeral:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  margin-tablet: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style
The design system targets modern property seekers, investors, and urban dwellers across Egypt and the broader MENA region. Built as an authoritative yet serene real-estate mobile prototype, the UI blends clean modernism with regional Arabic typographic fluency.

- **Brand Personality**: Trustworthy, premium, calm, structured, and friction-free.
- **Aesthetic Direction**: High-end modern utility. Neutral light canvas, generous whitespace, crisp structural cards, and deliberate touches of deep coastal navy with luminous teal accents.
- **Bi-Directional Dynamics**: Native RTL (Right-to-Left) reading flow with seamless English brand name framing ("Smart House Finder") preserved in clean Latin typography.
- **Emotional Response**: Reliability, clarity of property specs, and supreme confidence in browsing high-value transactions without sensory fatigue.

## Colors
The color architecture relies on a crisp high-trust palette engineered for rapid scanning of property listings, imagery, and pricing metrics:

- **Primary (`#1E2A38`)**: Deep Navy. Serves as the anchor for primary headlines, active navigation states, high-contrast badges, and dominant CTA fills.
- **Secondary / Accent (`#2A9D8F`)**: Mediterranean Teal. Communicates financial signals, featured property tags, dynamic pricing highlights, and positive validation.
- **Canvas / Background (`#F7F8FA`)**: Pale architectural alabaster, ensuring white property cards maintain clear spatial separation without aggressive borderlines.
- **Surface / Cards (`#FFFFFF`)**: Pure White for cards, bottom sheets, filter pills, and navigation bars.
- **Text & Neutral**:
  - Primary Text: `#222831` (Deep Charcoal) for optimal Arabic legibility and high contrast.
  - Secondary Text: `#6B7280` (Muted Slate) for specs (غرف، حمام، م²), subtitles, and metadata.
- **Borders & Dividers**: `#E5E7EB` for hairline separations.
- **System / Alert**: `#D9534F` (Terracotta Crimson) for favorite/heart activation, urgency alerts, and form validation errors.

## Typography
Typographic hierarchy is calibrated for RTL Arabic text balance, paired with clean Latin numerals and branding.

- **Primary Typefaces**: Arabic text defaults to modern, high-legibility geometric sans metrics (with `Cairo` / `Tajawal` as the foundational platform font, mapped cleanly into low-contrast, open-counter form factors). For Latin numerals and the primary English brand string, `Plus Jakarta Sans` delivers balanced geometric authority.
- **RTL Rhythm**: Arabic requires slightly taller line-height multipliers (minimum 1.45–1.5x) to accommodate natural ascenders, descenders, and diacritics without visual collision.
- **Directional Behavior**:
  - `dir="rtl"` enforced on root viewports.
  - Arabic body and headlines default to `text-align: right`.
  - Brand header "Smart House Finder" remains `ltr` inline.
  - Currency numerals and metrics (e.g., "3,500,000 ج.م" or "185 م²") preserve logical right-to-left layout with proportional digits.

## Layout & Spacing
A fluid 4-column layout tuned specifically for mobile handheld viewports (360px - 428px width), expanding into a centered 8-column layout on small tablets.

- **Screen Margins**: Fixed `16px` (`1rem`) on mobile canvas edges to maximize screen real estate for immersive property imagery.
- **Gutters**: Consistent `16px` between grid items and vertical stack elements.
- **RTL Coordinate Flow**:
  - Leading edges correspond to `margin-right` / `padding-right`.
  - Trailing elements (e.g., chevron disclosures, back buttons) flip horizontally along the vertical axis.
- **Vertical Rhythm**:
  - `8px` (`space-sm`) between spec badges and text metadata.
  - `16px` (`space-md`) between interior card elements.
  - `20px` (`space-lg`) section separation.
  - Bottom navigation offset incorporates standard iOS Home Indicator / Android navigation bar clearance (`padding-bottom: 24px` to `32px`).

## Elevation & Depth
Depth in the design system uses soft, wide-dispersion ambient drop shadows paired with crisp `#E5E7EB` borders. Heavy dark shadows are strictly prohibited to maintain an airy, daylight aesthetic.

- **Level 0 (Canvas Base)**: `#F7F8FA` flat base.
- **Level 1 (Property Cards & Chips)**: Surface `#FFFFFF`, border `1px solid #E5E7EB`, shadow `0 4px 20px -2px rgba(0, 0, 0, 0.06)`. This lifts listings above the alabaster background with a clean, physical presence.
- **Level 2 (Active Floating Controls & Badges)**:
  - Favorite Heart Button: Semi-translucent `#FFFFFF` background with `backdrop-filter: blur(8px)`, subtle border `1px solid rgba(255, 255, 255, 0.4)`, shadow `0 2px 8px rgba(0, 0, 0, 0.12)`.
  - Filter Chips (Active): Background `#1E2A38`, text `#FFFFFF`, zero shadow, flat authoritative presence.
- **Level 3 (Fixed Bottom Navigation Bar)**: Surface `#FFFFFF`, border-top `1px solid #E5E7EB`, shadow `0 -4px 16px rgba(0, 0, 0, 0.04)`. Anchors persistent access without visually suffocating the card feed.

## Shapes
A disciplined 16px (`1rem`) corner radius acts as the primary visual signature of the system, evoking architectural precision while remaining friendly and approachable.

- **Listing Cards**: `16px` outer container radius (`rounded-lg` token scale).
- **Listing Image Headers**: Top corners `16px`, bottom corners `0px` when flush with body, or full `12px` when floating inside padded card frames.
- **Pills, Spec Tags, and Action Buttons**:
  - Filter & Category Chips: Full rounded pill (`9999px`).
  - Spec Feature Badges (e.g., `3 غرف`): `8px` (`rounded-md`).
  - Interactive Form Inputs: `12px` radius.
  - Bottom Navigation Shell: Flat bottom, top corners subtly softened to `16px` or flush rectangle.

## Components

### 1. Property Card (Hero Component)
- **Container**: White `#FFFFFF`, `16px` border-radius, `1px solid #E5E7EB`, ambient shadow `0 4px 20px -2px rgba(0,0,0,0.06)`.
- **Image Header**: Aspect ratio `16:10`, overflow hidden, radius applied to top corners.
- **Favorite Badge**: Positioned at top-left (trailing position in RTL) of image, 36x36px circle, frosted glass white, containing an outlined heart icon; fills with `#D9534F` on selection.
- **Featured Tag**: Positioned at top-right (leading position in RTL), `#2A9D8F` teal background, white typography (`label-sm`), `4px 10px` padding, `6px` radius.
- **Content Area**: `16px` interior padding:
  - **Price Row**: Prominent primary display in `#2A9D8F` or `#1E2A38` (e.g., `٣,٢٥٠,٠٠٠ ج.م`), right-aligned.
  - **Title**: `#222831`, font size `16px`, weight `600`, max 1 line with ellipsis.
  - **Location Row**: Map-pin line icon followed by district/city name in `#6B7280`.
  - **Spec Divider Row**: Hairline border-top `#E5E7EB` with equal-spaced inline metrics:
    - `[غرف X]` | `[حمام X]` | `[م² X]`
    - Each unit paired with clean 16px line icons, text styled in `#6B7280` (`body-sm`), numerals highlighted in `#222831`.

### 2. 3-Tab Bottom Navigation
- **Structure**: Anchored persistent dock:
  - Tab 1: **الرئيسية** (Home)
  - Tab 2: **استكشف** (Explore / Map)
  - Tab 3: **المفضلة** (Favorites)
- **Layout**: Height `64px` plus device bottom inset. Three balanced RTL flex slots.
- **State Styling**:
  - Active: `#1E2A38` filled/bold icon, `#1E2A38` text label (`label-sm`), small `4px` teal dot indicator beneath label.
  - Inactive: `#6B7280` outline icon, `#6B7280` text label.

### 3. Header & Brand Bar
- **Brand Display**: Latin brand name `Smart House Finder` styled in `Plus Jakarta Sans` (bold, `#1E2A38`), left-to-right alignment, accompanied by a dynamic notification bell or search action placed at the opposite corner.
- **Search Bar**: Background `#FFFFFF`, border `1px solid #E5E7EB`, radius `12px`, with an integrated magnifying glass icon on the right edge (leading in RTL) and placeholder text "ابحث عن مدينة، حي، أو كمبوند..." in `#6B7280`.

### 4. Interactive Buttons & Chips
- **Primary CTA**: Background `#1E2A38`, text `#FFFFFF`, radius `12px`, min-height `48px`, tap feedback via subtle opacity shift to `0.9`.
- **Secondary / WhatsApp Action**: Background `#2A9D8F`, text `#FFFFFF`, radius `12px`.
- **Filter Chips**: Height `36px`, pill-shaped (`9999px`), border `1px solid #E5E7EB`, surface `#FFFFFF`, text `#222831`. Active state switches to `#1E2A38` background with `#FFFFFF` text.

### 5. Input Fields & Checkboxes
- **Input Fields**: Height `48px`, background `#FFFFFF`, border `1px solid #E5E7EB`, text-align right, padding right `16px`, focus state ring `2px solid #2A9D8F`.
- **Selection Controls**: Teal `#2A9D8F` active fills with white check indicators; RTL labels positioned with `8px` spacing to the left of the checkbox.