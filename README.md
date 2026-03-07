# HostedCSS

CSS overrides and branding styles for hosted GreenID and presales/demo environments.

## Stylesheets

- `greenid-bio-override-styles.css`  
	Main GreenID hosted override stylesheet. Includes typography, layout spacing, form control, and biometric journey visual overrides.

- `greenid-bio-override-styles-reactive.css`  
	Reactive-branded variant using `Outfit` typography and color variables, including responsive body/logo behavior.

- `greenid-bio-override-styles-reactive_harveynormancommercial.css`  
	Harvey Norman Commercial-specific reactive variant. Similar to the reactive stylesheet, with brand-specific color values (notably darker primary/logo treatment).

- `presalesdemoinstance.css`  
	Presales/demo environment stylesheet with targeted overrides for consent flow, DOB calendar/input controls, ConnectID, and biometric button/input presentation.

## How to use

1. Choose the stylesheet that matches the target environment/brand.
2. Attach it to the hosted page or include it in the environment where GreenID is rendered.
3. Verify key screens (desktop + mobile) before promoting changes.

## Maintenance notes

- Keep selectors scoped to GreenID containers where possible to avoid global side effects.
- Prefer updating the nearest matching variant rather than duplicating styles across files.
- Re-test responsive behavior whenever changing container width, logo, button, or typography rules.
