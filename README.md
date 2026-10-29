# Guangjun Ou · Personal Website

A minimal personal website with a white background and black text, featuring a short biography, GitHub avatar, the Leg-KILO project, an RA-L publication, and contact information. Built with plain HTML and CSS, with no dependencies to install.

## Local Preview

Open `index.html` in a browser, or run the following command in the project directory:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Editing

- `index.html`: name, biography, project, publication, and contact details.
- `styles.css`: layout, typography, and responsive styles.
- `assets/avatar.jpg`: the current GitHub avatar; replace it with your own photo if desired.
- `assets/backpack.png`, `assets/superloc.png`, `assets/nclt2.png`, `assets/diter.png`: the four original project images, displayed in a 2 × 2 grid. Click an image to open the full-size version.
- `assets/leg-kilo.png`: the publication image from `master/doc/fig/legkilo.png`, displayed beside the paper details in two equal columns on desktop and stacked on mobile.
- `script.js`: automatically updates the footer year.

The Chinese name appears beside the English name. All other page content is in English. All images are stored locally. The portrait has no border, rounded corners, or shadow. The project gallery keeps its two-column layout on mobile.

## Sources

- [GitHub profile](https://github.com/ouguangjun): avatar, background, ORCID, and public email address.
- [Leg-KILO](https://github.com/ouguangjun/Leg-KILO): project description, images, and citation. The original gallery images are `master/doc/fig/backpack.png`, `superloc.png`, `nclt2.png`, and `diter.png`, in that order.
- [Leg-KILO paper](https://doi.org/10.1109/LRA.2024.3440730): Guangjun Ou, Dong Li, Hanmin Li. *Leg-KILO: Robust Kinematic-Inertial-Lidar Odometry for Dynamic Legged Robots*. IEEE Robotics and Automation Letters, 9(10):8194–8201, 2024.

The project description covers the current repository. The publication section describes the original 2024 research.

## GitHub Pages

In the repository's **Settings → Pages**, select:

- Source：**Deploy from a branch**
- Branch：**main**
- Folder：**/ (root)**

Commit and push the website files to publish at `https://ouguangjun.github.io/`.
