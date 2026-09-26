# 🛰️ Palisades From Space

![Python 3.11](https://img.shields.io/badge/Python-3.11-B83F79?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-E68AB1?style=flat-square&logo=jupyter&logoColor=white)
![Sentinel-2 Level-2A](https://img.shields.io/badge/Sentinel--2-Level--2A-6C9279?style=flat-square)
![Normalized Burn Ratio](https://img.shields.io/badge/index-NBR-9782C7?style=flat-square)

**🌿 Before → 🔥 Fire → 🌱 Recovery check-in**

My little satellite project: using Python and Sentinel-2 Level-2A imagery to explore how the Palisades landscape changed across January 2025 and September 2026.

I compare near-infrared and shortwave-infrared light with the **Normalized Burn Ratio (NBR)**. A little look at what reflected light can tell us.

| Three moments, the same landscape | Date | Mean NBR |
| --- | --- | ---: |
| 🌿 Before | Jan 2, 2025 | **0.187** |
| 🔥 During the fire | Jan 17, 2025 | **−0.121** |
| 🌱 Recovery check-in | Sep 14, 2026 | **0.075** |

Across the same **91,659 clear land pixels**, a sharp drop is followed by a partial rebound in the satellite signal. Seasons and the study box matter too; this alone cannot establish ecological recovery.

✨ [Follow the story in my notebook](palisades_fire.ipynb).

**To rerun my little investigation**

Use Python 3.11 and install the notebook dependencies:

```bash
python -m pip install -r requirements.txt
```

Select that environment as your notebook kernel and run the cells from top to bottom. Rerunning needs internet access; the saved results are already in the notebook.

*Scene discovery: [Copernicus](https://dataspace.copernicus.eu/) · Analyzed imagery: [Earth Search, Collection 1](https://github.com/Element84/earth-search).*
