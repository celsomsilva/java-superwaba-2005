
# Sales Project (2005) - SuperWaba Framework

This repository contains a legacy mobile sales system developed in 2005 using the **SuperWaba** framework — a precursor to **Java ME** designed for portable applications running on Palm OS and Windows CE.

---

## 📜 About SuperWaba

**SuperWaba** evolved from the Waba project, a pioneering independent framework predating Java Platform, Micro Edition (Java ME). Initially supporting Palm OS, it later expanded to Windows CE devices.

Since version 5.0, SuperWaba integrated the SDL library for graphical display, enhancing its portability across different platforms.

**Note:** SuperWaba is now discontinued. Its official successor is **TotalCross**, which offers better cross-platform support, leaner compilation, improved performance, and a smaller footprint for mobile applications.

---

## 📁 Project Structure

```
superwaba/
└── sales/
    ├── bd/
    │   ├── ClienteBD.java
    │   ├── ItemDoPedidoBD.java
    │   ├── ParametrosBD.java
    │   ├── PedidoBD.java
    │   ├── ProdutoBD.java
    │   └── TabelaDePrecoBD.java
    │
    ├── ui/
    │   ├── cliente/
    │   ├── pedido/
    │   ├── produto/
    │   ├── relatorios/
    │   ├── BaseMenu.java
    │   └── MenuPrincipal.java
    │
    ├── DynamicTabPanel.java
    └── ForcaDeVendas.java
```

- **bd/** — Database-related classes and data access logic.
- **ui/** — User Interface modules, organized by feature (Clients, Orders, Products, Reports).
- **DynamicTabPanel.java** — Custom dynamic tab component.
- **ForcaDeVendas.java** — Main application controller for the Sales Force system.

---

## ⚠️ Disclaimer

This project is a **legacy application** and cannot be compiled or executed with modern Java environments. The repository is maintained solely for **historical reference** and code archival purposes.

---

## 📌 Notes

- No `src/` or `data/` folders are present, as the original environment setup and emulator dependencies are obsolete.
- No installation or usage instructions are provided, as SuperWaba is no longer supported.

---

## 📚 References

- [SuperWaba Official Archive (legacy)](https://web.archive.org/web/20080409173924/http://www.superwaba.org/)
- [TotalCross Mobile SDK](https://totalcross.com/)

---

## 📅 Author

**[Your Name]** — Developed during early mobile programming experiments in 2005.
