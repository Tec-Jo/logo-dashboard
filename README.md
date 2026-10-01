# logo-dashboard

Pressure dashboard for a Siemens LOGO! 8.4 that publishes to an EMQX Cloud MQTT broker.
Open it from any PC or phone: **https://tec-jo.github.io/logo-dashboard/** (after GitHub Pages is enabled).

- No secrets in this repository. The broker password is typed on each device and kept only in
  that browser (when "remember" is ticked).
- Source of truth and project notes: the private repository `Tec-Jo/Logo-HiveMQ` (`dashboard/`).
  This repository only publishes the page.
- `vendor/mqtt.min.js`: MQTT.js 5.16.0, MIT License (`vendor/MQTT.js-LICENSE.md`).
