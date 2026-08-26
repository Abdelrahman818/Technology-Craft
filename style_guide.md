# Technology Craft Style Guide

## Brand tone
- Professional, modern, and precise.
- Clear language that emphasizes craft, reliability, and operational value.
- Focus on readability, structured information, and accessible digital systems.

## Colour palette
- Page background: `#f7faff` (cool, nearly-white blue)
- Alternate section background: `#eef4fb`
- Surface panel: `#ffffff`
- Elevated surface: `#ffffff` with a soft blue-grey shadow
- Heading text: `#10233f` (deep navy)
- Body text: `#40536d`
- Muted text: `#6b7b91`
- Accent blue: `#1d4ed8`
- Accent cyan: `#0891b2`
- Accent highlight: `#dbeafe`
- Border/base: `#d7e2ef`
- Border strong: `#b8c9dc`
- Success: `#15803d`
- Warning: `#b45309`
- Error: `#be123c`

Use these as semantic tokens rather than styling individual components with arbitrary
colours. Text and interactive controls must maintain WCAG AA contrast against their
backgrounds. Reserve accent cyan for highlights and supporting details; use accent blue
for primary actions and links.

## Typography
- Hero heading: bold, large, clear navy text; use a restrained blue-to-cyan gradient only
	for a short highlighted phrase, never for an entire paragraph.
- Section headings: strong, clear, consistent scale across pages.
- Body copy: medium weight, relaxed line height, high contrast on white and pale-blue
	surfaces.
- Small text: uppercase labels, tracking-widest, muted text for metadata and support copy.
- Monospaced labels: use for metadata, step numbers, and code-like UI elements.

## Buttons & CTAs
- Primary button: rounded-full, accent blue background, white text, subtle blue shadow,
	smooth hover to a darker blue.
- Secondary button: white surface, navy text, visible base border, and a pale-blue hover
	state.
- Ghost button: transparent background, navy text, transparent-to-pale-blue hover state.
- Text link: underline or strong accent color for inline links.
- Keep spacing generous and legible. Every button needs a visible `:focus-visible` ring.

## Cards & panels
- Use modest rounded corners (`rounded-xl` or less) and solid white surfaces for elevated
	sections.
- Panels should use a clear border and a soft, cool shadow. Avoid relying on blur or
	transparency for legibility.
- Card hover states: slightly stronger border, a small upward lift, and a pale-blue surface
	tint. Keep the motion subtle and do not introduce gradients behind body copy.
- Content cards should balance a strong heading with concise body copy and clear feature lists.

## Animations
- Use gentle entrance animations: fade-up, fade-in, slide-in.
- Reserve motion for supporting emphasis, not core readability.
- Respect reduced motion where possible.
- Use consistent animation timing: 0.4s–0.8s with easing curves.

## Spacing & layout
- Section padding: generous top/bottom spacing (`py-24`, `py-28`) for page structure.
- Grid layouts: responsive columns with comfortable gutters.
- Use full-width containers with `mx-auto px-6 md:px-12` for page content.

## Navigation
- White or lightly translucent nav at top, with a white bordered surface after scroll.
- Primary nav links: Services, About, Work, Industries, Contact.
- CTA button in nav: Start a Project, using the primary button treatment.

## Icon system
- Use lucide icons consistently at `w-5 h-5` or `w-6 h-6` depending on context.
- Keep icon strokes medium-weight and color matched to accent states.
- Use icons to clarify sections, not clutter them.

## Shadow & glow
- Use a faint blue grid, soft radial light, or a quiet tonal shift behind hero and CTA
	sections to create depth without lowering text contrast.
- Avoid discrete blurred orbs and excessive glow effects.
- Shadows on cards should be subtle, cool-toned, and directional rather than black.

## Services taxonomy
- AI: chatbots and smart automations.
- Web development: static and dynamic websites, plus e-commerce.
- Mobile applications: React Native mobile apps.
- IT: consulting, help desk, networking, administration, devices, hosting, deployment.
- Designing: UI/UX design, graphic design, video editing, motion graphics, AI video.
- Marketing: SEO, paid campaigns, analytics, conversion optimization.

## Page-wide style rules
- Keep home page as the main brand experience.
- Other pages should match the same light visual system, with clear heading hierarchy and
	consistent white-panel styling.
- Do not use pure black text, low-contrast pale text, or dark surfaces as the default.
- Keep sections visually distinct through spacing, borders, and pale background bands rather
	than stacked cards or heavy gradients.
- Use semantic HTML sections and meaningful CTA links for SEO.
