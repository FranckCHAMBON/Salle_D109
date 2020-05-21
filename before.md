1. Installation de snapstore ou snapd
sudo pacman -S snapd
sudo systemctl enable --now snapd.socket
sudo ln -s /var/lib/snapd/snap /snap
sudo snap install snap-store

2. Installation de VSCodium
    * avec HackMD
    * paquets French...
3. Installation de pip
4. Environnement de travail

   `python3 -m venv mkdocs`
5. paquets
    ```
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

Pygments
markdown
pymdown-extensions
mkdocs-material
mkdocs-git-revision-date-localized-plugin
mkdocs-minify-plugin

6. VSCode multi cursor
gsettings set org.cinnamon.desktop.wm.preferences mouse-button-modifier "<Super>"