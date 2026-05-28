# AI-Augmented MPC for Safe and Adaptive Spacecraft RPO

Project webpage for:

**AI-Augmented Model Predictive Control for Safe and Adaptive Rendezvous and Proximity Operations**

Developed at Embry-Riddle Aeronautical University in collaboration with  
[XDLab — Exploration and Digital Laboratory](https://xdlab.space/)

Website:  
https://lucasportelli35.github.io/ai-augmented-mpc/

---

## Overview

This repository contains the source files for the project webpage associated with the research effort on AI-augmented Model Predictive Control (MPC) for autonomous spacecraft rendezvous and proximity operations (RPO) in adversarial orbital environments.

The proposed framework combines:

- Constrained receding-horizon MPC
- Predictive safety-aware trajectory optimization
- Online adaptive supervisory tuning
- Interpretable parameter adaptation
- Multi-agent adversarial spacecraft interaction

A key design principle of the architecture is that the AI layer does **not** directly command spacecraft thrust. Instead, it supervises and adapts high-level MPC optimization parameters while the MPC layer remains responsible for generating control commands under orbital dynamics, actuator limits, and predictive safety constraints.

---

## Competition Context

This work is connected to the Embry-Riddle XDLab effort evaluated in the official:

**AIAA Capture the Satellite Challenge**

The team achieved **First Place** in the competition using adaptive spacecraft-control strategies in a real-time adversarial rendezvous scenario.

Related articles:

- Aerospace America  
  https://aerospaceamerica.aiaa.org/institute/gotcha-students-capture-malfunctioning-satellite-in-spacecraft-control-exercise/

- Embry-Riddle News  
  https://erau.edu/about/news-and-stories/news/embry-riddle-student-team-earns-first-place-in-capture-the-satellite-competition

---

## Repository Structure

```text
index.html        Main webpage
style.css         Website styling
assets/           Figures and images used in the webpage
README.md         Repository documentation
```

---

## Main Features of the Webpage

- Research-project landing page
- Responsive layout for desktop/mobile
- Project overview and methodology
- Monte Carlo robustness results
- Controller comparison figures
- Interpretability analysis
- Competition recognition section
- BibTeX citation block
- External article and lab links

---

## Deployment

The webpage is hosted using **GitHub Pages**.

### Update Procedure

1. Open the GitHub repository.
2. Click:
   ```text
   Add file → Upload files
   ```
3. Replace the modified files:
   - `index.html`
   - `style.css`
   - `README.md`
   - `assets/`
4. Click:
   ```text
   Commit changes
   ```
5. Wait approximately 1–3 minutes.
6. Refresh the GitHub Pages website.

---

## Future Additions

Planned future improvements include:

- Public paper link / DOI
- arXiv preprint
- Source-code repository
- Simulation video or GIF
- Interactive plots
- Additional experiment results
- Dark mode support
- Extended mobile optimization

---

## Citation

```bibtex
@article{sportelli2026ai_augmented_mpc,
  title  = {AI-Augmented Model Predictive Control for Safe and Adaptive Rendezvous and Proximity Operations},
  author = {Sportelli, Luca and Barr, Tyler and Kilic, Cagri and Wu, Di},
  journal = {Under review},
  year   = {2026}
}
```

---

## Authors

Luca Sportelli  
Tyler Barr  
Cagri Kilic  
Di Wu

Department of Aerospace Engineering  
Embry-Riddle Aeronautical University

XDLab — Exploration and Digital Laboratory  
https://xdlab.space/
