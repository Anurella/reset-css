# Custom CSS reset

Browsers ship with default styles. Those defaults can create or seem like inconsistencies when building across different browsers—for example, differences in line-height can affect spacing, height, and alignment.

While browser standards have improved over time and inconsistencies have reduced, defaults still vary enough that a reset stylesheet remains a useful starting point.

One of the earliest widely used reset stylesheets was [Eric Meyer's](https://meyerweb.com/eric/tools/css/reset/) (2011). Eric recommended tailoring resets to suit your needs. A lot has changed since then, so this project provides an updated, generic reset you can adapt.

This reset stylesheet is a collection based on real usage from work done and inspection of modern, well-built sites. It’s intended to be a strong baseline that you can modify to suit your needs.

---

## Getting Started

1. Copy the reset.css file into your project
2. Import it at the top of your main stylesheet so it loads before your app styles.

```css
 @import "./reset.css";
```

---

### Note

* Apply the reset as the starting base of a project - best applied that way.
* Avoid introducing it into an existing codebase unless you are prepared to address layout/style changes.

---

