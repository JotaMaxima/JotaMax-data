# Bases y Condiciones Oficiales de la Hackatón Dev3pack (Solana)

El presente documento establece los lineamientos, requisitos técnicos, criterios de evaluación y condiciones de participación para la **Hackatón Dev3pack**, diseñada para impulsar la creación de startups e infraestructura descentralizada en el ecosistema Solana a través de pistas regionales en Latinoamérica y España.

---

## 1. Marco General y Elegibilidad de Participantes

La Hackatón Dev3pack constituye la fase de competición práctica posterior al bootcamp formativo. Su objetivo central es transformar los conceptos aprendidos en productos mínimos viables (MVP) funcionales desarrollados sobre la red de Solana.

### Pistas Regionales y Formato de Equipos
* **Elegibilidad Geográfica**: La competición cuenta con *tracks* locales adaptados para participantes de Latinoamérica y España (incluyendo Argentina, Perú, Costa Rica, Ecuador, entre otros países de la región).
* **Formación de Equipos**: La participación puede realizarse de forma individual o en equipos. El número mínimo y recomendado de integrantes por grupo se confirma mediante la plataforma y el canal oficial de comunicación de Dev3pack.
* **Integración Comunitaria**: Los proyectos reciben acompañamiento de las comunidades locales de Superteam para facilitar el desarrollo técnico e institucional.

---

## 2. Requisitos Técnicos y Entregables del Proyecto

Para que un proyecto sea formalmente evaluado por el jurado técnico, debe cumplir estrictamente con los siguientes entregables y estándares de desarrollo:

### Checklists de Entregables Obligatorios

* **Programa On-Chain Desplegado**:
  * Código desarrollado en **Rust** utilizando el framework **Anchor**.
  * Despliegue activo en la red **Devnet** o **Mainnet Beta**.
  * Archivo de interfaz de IDL generado y publicado (por ejemplo mediante Codama o `solana-verify`) para permitir la inspección transparente del programa en exploradores de bloques.

* **Cliente Frontend e Integración de Interfaz**:
  * Interfaz de usuario conectada mediante el SDK moderno **Solana Kit** (`@solana/kit`), `create-solana-dapp` o clientes tipados.
  * Uso de proveedores RPC con límites de tasa adecuados (como Helius, Triton, QuickNode o Alchemy) para asegurar la fluidez de la aplicación durante las pruebas.

* **Repositorio de Código Fuente y CI en Verde**:
  * Repositorio público en **GitHub** con integración continua (CI) configurada y ejecutándose correctamente.
  * Cobertura de pruebas unitarias e integración en verde utilizando entornos de prueba como LiteSVM o Anchor tests desde el primer día de desarrollo.

* **Video Demo de 60 Segundos**:
  * Demostración en video con una duración exacta de 60 segundos que exhiba la ejecución de transacciones reales interactuando con el programa on-chain en tiempo real.

* **Explicación de Arquitectura y Validación de Renta**:
  * Documentación breve dentro del repositorio donde el equipo explique el modelo de datos (cuentas y PDAs) y la gestión del saldo mínimo para exención de renta (*rent exemption*).

---

## 3. Criterios de Evaluación y Filtros del Jurado

El jurado prioriza soluciones que exploten de manera genuina la arquitectura de alto rendimiento de Solana, descartando proyectos superficiales.

### Filtros Principales de Evaluación

1. **Nivel de Integración Profunda con Solana**:
   * Se evalúa si el proyecto aprovecha las capacidades nativas de la red (programas custom en Rust, PDAs, cuentas de datos, tokens SPL / Token-2022).
   * Proyectos que solo integren transferencias básicas de USDC o llamadas simples a agregadores como Jupiter sin lógica on-chain propia no reciben puntuación técnica relevante.

2. **Impacto y Originalidad del Caso de Uso**:
   * Se busca resolver problemas reales con impacto directo en el mercado local o global.
   * Se prioriza la innovación en sectores como Finanzas Descentralizadas (DeFi), infraestructura o herramientas avanzadas, evitando la duplicación de aplicaciones de pago genéricas (*Payment Hubs* sin propuesta diferencial).

3. **Calidad de Código y Seguridad**:
   * Verificación de buenas prácticas en Rust (gestión segura de memoria, ausencia de desbordamientos y control estricto de firmas/signers y propietarios/owners de cuentas).
   * Despliegue auditable y pruebas automatizadas pasando correctamente.

---

## 4. Política sobre el uso de Inteligencia Artificial

Dev3pack promueve el aprendizaje acelerado mediante asistentes de código e Inteligencia Artificial bajo reglas claras de autoría y comprensión:

* **Asistencia Permitida**: Se autoriza el uso de herramientas de IA (como Claude, ChatGPT o asistentes de la plataforma) para aclaración de conceptos, sugerencias de sintaxis y aceleración de prototipos.
* **Requisito de Comprensión Real**: Todo equipo debe ser capaz de defender y explicar la arquitectura de su programa, la lógica de las instrucciones y los cálculos de validación de renta. El código generado automáticamente sin comprensión técnica por parte del equipo no es admisible.

---

## 5. Premios, Certificación y Programa de Aceleración

La Hackatón Dev3pack actúa como puente directo hacia la creación de empresas Web3 viables.

* **Certificación Oficial**: Los participantes que alcancen el porcentaje requerido en las evaluaciones del bootcamp y desplieguen con éxito su programa en Solana reciben su certificado oficial de desarrollo.
* **Acceso al Programa de Aceleración (Accelerator)**: Los **Top 2 proyectos clasificados por país** avanzan de forma directa al programa de aceleración regional, donde reciben mentoría especializada, soporte institucional y acceso a capital de riesgo para escalar su MVP a una startup en producción.

---

## 6. Alcance de la Información y Canales Oficiales

Las presentes bases resumen las reglas técnicas, criterios de filtrado y estructura de entrega derivadas del bootcamp Dev3pack. 

Para consultar el cronograma de fechas límite de entrega, la bolsa específica de premios en efectivo por categoría y el registro de equipos para la edición vigente, los participantes deben verificar la información actualizada directamente en la plataforma Dev3pack y en los canales oficiales de Telegram del programa.
