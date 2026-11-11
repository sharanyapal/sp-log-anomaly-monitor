<div align="center">

# Log Anomaly Radar

**Treat unusual log patterns as signals to investigate.**

<sub>Security analytics &nbsp; · &nbsp; Python &nbsp; · &nbsp; Practical lab</sub>

[Purpose](#purpose) · [Run](#run-the-lab) · [Inspect](#repository-guide) · [Boundaries](#scope--boundaries)

</div>

---

## Purpose

Robust median-absolute-deviation spike detection with timestamped incident output.

This repository keeps the implementation close to its inputs so you can inspect the decisions it makes. The emphasis is on understanding a reproducible example, rather than claiming production-grade behavior.

## Run the lab

```bash
python main.py
```

A `requirements.txt` file is included; check it for environment dependencies before running.

## Repository guide

| Path | What to look for |
|:--|:--|
| [`.gitignore`](./.gitignore) | Ignored local artifacts |
| [`README.md`](./README.md) | Project guide |
| [`main.py`](./main.py) | Python entry point and program logic |
| [`requirements.txt`](./requirements.txt) | Dependency specification |
| [`test_main.py`](./test_main.py) | Included Python tests |

## Questions worth exploring

- Which inputs lead to a different result, and why?
- How does the program behave with empty, unusual or inconsistent data?
- What assumptions would need to change before using the technique in a larger system?

## Scope & boundaries

The repository is an educational or portfolio-scale implementation. Use synthetic or non-sensitive examples and review the original notes before adapting it. No deployment or security certification is implied.

<details>
<summary><strong>Original documentation</strong></summary>

# Log Anomaly Radar

Robust median-absolute-deviation spike detection with timestamped incident output.

## Run

```bash
python main.py
```


No third-party dependencies are required.

## Notes

Demonstration code uses local, synthetic, or publicly available sample data. No proprietary banking/client data.


---

**Part of Sharanya Pal's coding portfolio:** https://sharanya-pal-cinematic-portfolio.vercel.app/#lab-vault  \n**GitHub repository:** https://github.com/sharanyapal/sp-log-anomaly-monitor

</details>

---

<sub>Part of [Sharanya Pal's GitHub projects](https://github.com/sharanyapal?tab=repositories) · Documentation grounded in checked-in code.</sub>
