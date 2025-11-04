
![Java](https://img.shields.io/badge/Java-5-007396?logo=java&logoColor=white)
![Pioneering Mobile Tech](https://img.shields.io/badge/Pioneering_Mobile_Tech-2005-orange)
![Eclipse](https://img.shields.io/badge/Eclipse-IDE-2C2255?logo=eclipseide&logoColor=white)
![License](https://img.shields.io/github/license/celsomsilva/java-superwaba-2005)





# Sales - Java Mobile Project (2005)

<**Note:** This repository contains the original version in Portuguese.  You will find the repository that contains the English-translated version here: [java SuperWaba 2005 en](https://github.com/celsomsilva/java-superwaba-2005-en, including file names, variables, methods, and comments.

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
java-superwaba-2005/
└── sales/
    ├── bd/
    │   ├── ClienteBD.java
    │   ├── ItemDoPedidoBD.java
    │   ├── ParametrosBD.java
    │   ├── PedidoBD.java
    │   ├── ProdutoBD.java
    │   └── TabelaDePrecoBD.java
    │
    ├──ui/
    │	├── cliente/
    │   │	├── ClienteCreditos.java    
    │   │	├── ClienteEnderecoDeCobranca.java    
    │   │	├── ClienteEnderecoDeEntrega.java
    │   │	├── ClienteEndereco.java    
    │   │	├── ClienteGeral.java   
    │   │	├── ClienteMaisEndereco.java    
    │   │	├── ClienteMaisInfo.java    
    │   │	├── ClientesMenu.java    
    │   │	├── NovoCliente.java    
    │   │	└── ProcuraClientes.java   
    │	│        
    │	├── produto/
    │   │	├── NovoProduto.java
    │   │	├── ProcuraProdutos.java
    │   │	└── ProdutosMenu.java
    │	│
    │	├── pedido/
    │   │	├── ItemsDoPedido.java
    │   │	├── NovoPedido.java
    │   │	├── PedidoGeral.java
    │   │	├── PedidoTabelaDePreco.java
    │   │	├── PedidosMenu.java
    │   │	└── ProcuraPedidos.java
    │	│
    │	├── relatorios/
    │   │	├── RelatorioMenu.java
    │   │	├── sumariodevendas/
    │   │	│   ├── Anual.java
    │   │	│   ├── Diario.java
    │   │	│   ├── Mensal.java
    │   │	│   ├── PorPeriodo.java
    │   │	│   └── SumarioDeVendasMenu.java
    │   │	│
    │   │	└── vendasporproduto/
    │   │	    ├── Anual2.java
    │   │	    ├── Diario2.java
    │   │	    ├── Mensal2.java
    │   │	    ├── PorPeriodo2.java
    │   │	    └── VendasPorProdutoMenu.java
    │	│
    │	├── BaseMenu.java
    │	└── MenuPrincipal.java
    │
    ├── DynamicTabPanel.java
    └── ForcaDeVendas.java

```

> **Note:** Due to the deprecation of the SuperWaba platform, this project is no longer executable. It remains available for historical and educational purposes.

---


## About the Refactoring

This repository focuses on source code preservation and translation rather than execution.  
The original SuperWaba SDK is no longer maintained, and rebuilding the environment is unnecessary for documentation purposes.
All refactoring (class, variable, and comment translation) was performed directly in Eclipse without dependency resolution.


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


---


## About the Author

I’m a Data Science and Analytics specialist (USP postgraduate) and Computer Engineer (UERJ) with a career spanning from **Pascal/C/Java roots** to **modern Machine Learning and AI**.

My academic and professional background includes:

- **Computation in general**
- **Machine Learning**
- **Hierarchical nonlinear mixed models (HLM3/HLM2)**, **Intraclass correlation (ICC)** and other topics about **HLM**
- **Residual diagnostics and model validation**
- **Deep Learning, LLMs, and Reinforcement Learning (ongoing specialization)**


---

## Contact  

- [LinkedIn](https://linkedin.com/in/celso-m-silva)  
- Or open an [issue](https://github.com/celsomsilva/java-suerwaba-2005/issues)
