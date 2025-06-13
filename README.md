# MiBolsillo – Descripción del Proyecto

**MiBolsillo** es una aplicación web desarrollada en .NET, diseñada para ayudar a individuos y familias a gestionar sus finanzas personales. Su propósito es ofrecer una herramienta sencilla pero poderosa para registrar ingresos, gastos y visualizar hábitos de consumo con claridad.

---

## **👥 Integrantes**  

| Name                    | Role       | CV´s                                         |
|-------------------------|------------|----------------------------------------------|
|Brayan Palma Aboytes     |Scrum master|<a href="https://oscaarc82.github.io/oscar.github.io/"> Curriculum </a>|
|Oscar Ulises Ramirez Cruz|Developer   |<a href="https://oscaarc82.github.io/oscar.github.io/"> Curriculum </a>|


---

## Características Principales (MVP)

- **Autenticación de Usuarios:** Registro e inicio de sesión con credenciales seguras.
- **Registro de Transacciones:** Agrega ingresos o gastos, con monto, fecha, descripción y categoría.
- **Gestión de Categorías:** Crea, edita o elimina categorías de ingresos/gastos.
- **Historial de Transacciones:** Lista cronológica con filtros y paginación.
- **Dashboard Financiero:** Saldo actual, resumen mensual y desglose por categorías.

---

## Público Objetivo

Dirigido a cualquier persona que desee mejorar su control financiero:  
Desde estudiantes hasta familias que buscan optimizar sus gastos mensuales.

---

## Metodología

Se aplica la metodología **Scrum** por su enfoque iterativo e incremental, ideal para adaptarse a cambios y entregar valor continuo en ciclos cortos (Sprints).

---

## Herramientas Utilizadas

- **.NET (ASP.NET Web Forms)** – Backend y capa de presentación.
- **GitHub** – Control de versiones, Pull Requests e Issues.
- **Trello** – Gestión visual de tareas y progreso. <a href="https://trello.com/b/djA8zJT9/desarrollo-web-integral"> Acceder</a>
- **ADO.NET / LINQ to SQL** – Acceso a datos.

---

## Arquitectura del Proyecto

### Arquitectura en Capas (N-Tier):
- **Presentación (UI):** Páginas .aspx y code-behind (.aspx.cs).
- **Lógica de Negocio (BLL):** Clases C# con reglas de negocio.
- **Acceso a Datos (DAL):** CRUD sobre la base de datos.

### Aplicación del patrón MVC (de forma conceptual en Web Forms):
- **Modelo:** Clases de datos como Usuario, Transacción, Categoría.
- **Vista:** Interfaces .aspx con controles de presentación.
- **Controlador:** Code-behind que conecta la vista con la lógica.

---
