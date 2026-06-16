# Underwater Datasets Collection

A curated collection of **164 underwater datasets** organized into 4 categories.

## Why Underwater Datasets Matter

The underwater environment is one of the final frontiers on Earth — covering over 70% of the planet's surface, yet largely unexplored. Underwater perception technologies (sonar, optical imaging, cross-modal sensing) play a critical role in marine science, environmental monitoring, offshore engineering, underwater robotics, and resource exploration.

However, researchers and engineers in this domain often face a fragmented landscape: datasets are scattered across different platforms, hidden behind paywalls, or remain unpublished. For newcomers, simply finding the right dataset can be a significant barrier.

**This repository was created to address this problem** — to provide a centralized, well-organized, and continuously updated reference for underwater datasets, helping researchers and practitioners quickly locate the data they need.

### Why Four Categories?

Underwater perception is not a one-size-fits-all problem. Different sensing modalities capture fundamentally different aspects of the underwater world, each with its own strengths, limitations, and application scenarios. We organize datasets into four categories based on the underlying sensor technology:

| Category | Sensor Type | Typical Applications |
|----------|------------|---------------------|
| **Side-scan Sonar** | Towed or hull-mounted acoustic arrays | Seabed mapping, mine detection, shipwreck discovery, habitat classification |
| **Forward-looking Sonar** | Forward-mounted multibeam/imaging sonar | Obstacle avoidance, AUV navigation, underwater inspection, target tracking |
| **Optical Image** | Cameras (RGB, stereo, polarization, light field) | Coral reef monitoring, fish detection, marine debris cleanup, image enhancement |
| **Optical-Sonar Cross-modal** | Combined optical + acoustic sensors | Multimodal fusion, cross-modal translation, robust perception in turbid environments |

This taxonomy reflects the natural division in the research community: **sonar** (both side-scan and forward-looking) excels at long-range, turbidity-immune perception but produces low-resolution, noisy imagery; **optical** sensors deliver rich texture and color but are severely limited by water clarity and lighting conditions; **cross-modal** approaches aim to combine the best of both worlds — a frontier that is rapidly gaining attention. By separating datasets along these lines, researchers can quickly find the data relevant to their specific modality or fusion task.

## Categories

| Category | Dataset Count |
|----------|:------------:|
| [Side-scan Sonar Datasets](side-scan-sonar-datasets/) | 28 |
| [Optical-Sonar Cross-modal Datasets](optical-sonar-cross-modal-datasets/) | 13 |
| [Optical Image Datasets](optical-image-datasets/) | 104 |
| [Forward-looking Sonar Datasets](forward-looking-sonar-datasets/) | 19 |
| **Total** | **164** |

## Structure

```
├── side-scan-sonar-datasets/
│   └── README.md
├── optical-sonar-cross-modal-datasets/
│   └── README.md
├── optical-image-datasets/
│   └── README.md
├── forward-looking-sonar-datasets/
│   └── README.md
└── README.md
```

## Usage

- Each category folder contains a `README.md` listing all datasets in that category.
- If a dataset has a public link, only the link is provided.
- If a dataset has no link, the reference paper title is listed instead.

## ⚠️ Important Notes

### Datasets Without Links
Some datasets in this collection do not have direct download links. This is because the original authors may not have publicly released the data at the time of collection, or the dataset is described in a paper but not yet openly available. In such cases, we provide the corresponding **paper title** so that interested researchers can locate the original work and contact the authors if needed.

### Corrections & Contributions
This is a community-driven effort, and errors are inevitable. Some links may be outdated, broken, or point to incorrect resources. **We warmly welcome:**

- 🔧 **Error corrections** — if you find a broken or incorrect link, please open an issue or submit a pull request.
- ➕ **New datasets** — if you know of an underwater dataset not yet listed here, feel free to contribute by adding it to the appropriate category.
- 📝 **Link updates** — if a dataset that currently only has a paper reference has since been made publicly available, please help us update the link.

Together we can make underwater research more accessible for everyone.

---

