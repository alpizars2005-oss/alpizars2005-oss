# Profile README redesign plan

## Goal

Redesign the `alpizars2005-oss/alpizars2005-oss` profile README as a compact PizzaLab-inspired technical profile while preserving public privacy and evidence boundaries.

## Research baseline

- Current profile repository and README.
- `alpizars2005-oss/aalfredo-dev` as the authoritative public wording/evidence boundary.
- Public project repositories for Job Search Assistant, Mochi Mochi, UCAMP Projects, Ultimate Macro Remote, Alpizers Releases, and IT automation practice.
- `macu-dev/macu-dev` only for high-level composition and hierarchy. No text, SVG, identity, or assets will be copied.

## Design rules

- Public display name: **Angel Alfredo** only.
- PizzaLab palette:
  - background `#0D1117`
  - panel `#181E27`
  - border `#343B46`
  - primary `#F0F3F6`
  - secondary `#B8C7E0`
  - accent `#FF9B63`
  - soft accent `#FFB07A`
  - muted `#8B949E`
- One original static SVG header; no copied or externally hosted artwork.
- No fake live metrics, profile counters, animated typing, rainbow badge walls, unsupported claims, or completed-degree language.
- Private work is explicitly labeled private; community contributions and coursework are separated from owned public projects.

## Planned commits

1. **Document profile README redesign plan**
   - Add this implementation and validation plan.
2. **Add PizzaLab profile header asset**
   - Add an original static SVG under `assets/`.
3. **Redesign GitHub profile README**
   - Replace the starter README with the complete PizzaLab profile.
   - Use verified public links and concise stack/project descriptions.

## Validation

- Re-fetch the final README and SVG from GitHub.
- Check every repository/project URL used in the README.
- Check the public portfolio URL.
- Confirm every relative asset path resolves.
- Search final public files for full surnames or unsupported education claims.
- Confirm private/public/contribution/coursework labels are explicit.
- Review phrasing for inflated experience, simulated telemetry, and generic AI-style copy.

## Rollback

Each change is isolated in its own commit. Revert the README commit to restore content, the asset commit to remove the visual header, and the plan commit to remove project notes.
