# DMODT‑Tracking‑Demos

Qualitative tracking results for **DMODT – Dynamic Maritime Object Detection and Tracking**.  
DMODT was developed to boost situational awareness for Maritime Autonomous Surface Ships (MASS) by:

* **Edge‑aware detection** – a Maritime Multi‑scale Edge Enhancement (MMEE) backbone highlights subtle ship boundaries hidden by waves and glare.  
* **Robust tracking** – an Observation‑Centric Kalman Filter (OCKF) plus a Height‑Modulated IoU (HMIoU) and RHOCME horizontal‑momentum cues keep identities stable under occlusion, camera heave and non‑linear motion.  
* **Proven gains** – on the Singapore Maritime Dataset DMODT lifted HOTA ↑ 33.8 %, MOTA ↑ 10.3 % and IDF1 ↑ 43.4 % versus a strong ByteTrack+YOLOv7 baseline. :contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}

<div align="center">
  <img src="DMODT_0801.gif" alt="Key‑frame demo" width="70%">
</div>

---

## Demo contents

| Folder / file | Description |
|---------------|-------------|
| `*.gif`       | Key‑frame animations (≈ 10 FPS) for a quick look at identity consistency. |
| `raw_videos/` | High‑resolution MP4s (original frame rate, bounding‑box overlays, ID trails). |

Raw videos are hosted externally because of size limits:

