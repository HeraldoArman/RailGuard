# RailGuard

> 🥉 **3rd Place Winner — HackSphere 2025 (COMPSPHERE 11)**
> Awarded a 3,000,000 IDR prize

RailGuard is a crowd-crush prevention system for KRL stations: a custom YOLO
model trained on Jakarta station footage counts passengers at each gate and
pushes density alerts to a Next.js PWA used by officers on the ground. CCTV
feeds are processed locally and only aggregate counts go upstream, so alerts
fire within seconds when a gate crosses a configurable threshold; the
installable PWA enables offline push notifications during network outages.

Built for HackSphere, a national 48-hour hackathon by COMPSPHERE (October 2025).

RailGuard is split across two submodules:

- [`RailGuard-PWA`](https://github.com/HeraldoArman/RailGuard-PWA) — web app.
- [`kai-ai-model`](https://github.com/Delta-K-rist/kai-ai-model) — AI model.

Clone with submodules:

```sh
git clone --recurse-submodules https://github.com/HeraldoArman/RailGuard.git
```
