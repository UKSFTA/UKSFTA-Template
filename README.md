# UKSFTA Project Template

The standard foundation for new UKSFTA mod projects. Includes pre-configured HEMTT settings and the UKSFTA-Tools submodule.

## 🏗 Setup a New Project

1. **Clone & Init**:
   ```bash
   git clone --recursive [YOUR_REPO_URL]
   ```

2. **Configure**:
   - Update `name` and `workshop_id` in `.hemtt/project.toml`.
   - Add dependencies to `mod_sources.txt`.

3. **First Build**:
   ```bash
   python3 tools/manage_mods.py
   hemtt build
   ```
