# AMOLED Peach
HA Theme with peach & pastel colours

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

### Screenshots
**1. Desktop**
<p align="center">
  <img src="">
</p>

**2. Mobile**
<p align="center">
  <img src="">
</p>

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

<pre>
frontend:
  themes: !include_dir_merge_named ../themes
</pre>

2. Under the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes. 

### HACS installation
1. Go into the Community Store (HACS)
2. Search for Peach
3. Open the theme
4. Press Install
5. Restart Home Assistant

### Manual installation
1. In the Home assistant **themes** folder, create a file named `peach.yaml`
2. In this GitHub repo, go into the **themes** folder, open the `peach.yaml` file and copy the content
3. Paste the content in the `peach.yaml` file created under your Home Assistant themes folder

### Enable theme
1. Open your Home Assistant **Profile**
2. Under, **Themes**, select the new Peach theme
