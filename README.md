# UKSFTA Project Template

Standard foundation for new UKSFTA mod projects. Includes pre-configured
HEMTT settings and the UKSFTA-Tools submodule.

## Setup a New Project

1. **Clone and init**:
   ```bash
   git clone --recursive [YOUR_REPO_URL]
   ```

2. **Configure**:
   - Update `name` and `workshop_id` in `.hemtt/project.toml`.
   - Add dependencies to `mod_sources.txt`.

3. **First build**:
   ```bash
   python3 tools/manage_mods.py
   hemtt build
   ```

## What is Included

- `.hemtt/project.toml`: Pre-configured HEMTT project file.
- `tools/`: UKSFTA-Tools submodule for build automation.
- `mod_sources.txt`: Dependency list for Workshop synchronisation.

## Licence

This project is licensed under the Arma Public Licence (APL). See the
`LICENSE` file.
