# Sales - SuperWaba Project (2005)

This is a legacy project developed in 2005 using **SuperWaba**, a mobile development platform derived from the **Waba project**, an early pioneer in mobile Java development (pre-Java ME).

The main application, `Sales`, was built for mobile devices running **Palm OS** and **Windows CE** platforms.

---

## About SuperWaba

SuperWaba evolved from the Waba project, initially supporting Palm OS devices and later expanding to Windows CE and other platforms via SDL from version 5.0. It was a popular option in Brazil for enterprise mobile applications throughout the early 2000s.

> **Note:** SuperWaba is no longer maintained. Its successor, **TotalCross**, is a modern, lightweight mobile SDK offering improved performance and cross-platform support.

---

## About This Project

The `Sales` application was developed in **2005** as part of one of the **startups incubated at PUC-Rio (Pontifical Catholic University of Rio de Janeiro)**.

The goal was to create a portable, lightweight, and efficient mobile sales force management system for handheld devices used by sales teams in the field.

**Main functionalities:**
- Client management  
- Product catalog management  
- Price table handling  
- Order entry and tracking  
- Sales reporting and dashboards  

---

## Project Structure

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

> **Note:** Due to the deprecation of the SuperWaba platform, this project is no longer executable. It remains available for historical and educational purposes.

---

## Institutional Use

SuperWaba was officially adopted in large-scale projects in Brazil, including government-led initiatives. Notably:

In **2009**, the **Brazilian Ministry of Planning, Budget and Management**, through the **IBGE (Brazilian Institute of Geography and Statistics)**, issued an official tender for the **migration of the Censo 2010 mobile application from SuperWaba to TotalCross**.

**Official Tender Highlights:**
- **Tender:** Pregão Eletrônico Nº 76/2009  
- **Service:** Migration of Censo2010 mobile application from SuperWaba to TotalCross  
- **Included Deliverables:**
  - Full code review and optimization for TotalCross
  - Workshop to train a 15-person internal IBGE team on TotalCross technology and source code updates
  - Licensing of **260,000 virtual machines** for a one-year period

**Source:** Brazilian Ministry of Planning and IBGE (2009)


---

## Disclaimer

This project is preserved for historical, academic, and educational purposes only. It represents mobile development practices from the early 2000s and should not be used for production systems.
