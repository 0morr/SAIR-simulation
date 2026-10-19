# SAIR Model Simulator

An interactive web simulator of computer-virus propagation based on the SAIR epidemiological model proposed by Piqueira, Navarro & Monteiro (2005).

A single-file web app that lets you explore how a computer virus spreads through a network under different conditions, and see in real time whether the outbreak dies out or becomes endemic.

---

## Features

- Live parameter control: adjust population size, infection, recovery, isolation and antivirus rates with sliders.
- Threshold analysis: computes the reproduction number R01 and the critical limit beta_limit (Eq. 18) on the fly.
- Regime indicator: shows whether the network is safe (R01 < 1) or in epidemic alert (R01 > 1).
- Real-time visualization: A / S / I / R population curves rendered with Chart.js.
- Accurate integration: 4th-order Runge-Kutta (RK4) solver instead of naive Euler.
- Responsive and accessible: semantic HTML, ARIA live regions, keyboard-friendly.

---

## Quick start

No build step, no `npm install`. Just open the file:

```bash
git clone https://github.com/0morr/SAIR-simulation.git
cd sair-model-simulator
# open index.html in any modern browser
