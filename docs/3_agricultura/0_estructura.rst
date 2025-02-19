===================================
Estructura del modelo
===================================

El sector agrícola analiza la producción de productos alimenticios como frutas, vegetales, hortalizas y productos cárnicos. Este sector registra emisiones de gases como metano (CH4), óxido nitroso (N2O), óxidos de nitrógeno (NOx), monóxido de carbono (CO) y dióxido de carbono (CO2). Las categorías utilizadas se basan en el INGEI de la 5ta Comunicación Nacional (5CN) del Ecuador (MAATE, n.d.).

Categorías del INGEI
---------------------

.. list-table:: Tabla 1. Categorías del INGEI consideradas en el modelo de agricultura
   :header-rows: 1

   * - Código
     - Descripción
     - Gas
   * - 3A1
     - Emisiones de CH4 por fermentación entérica en el ganado doméstico
     - CH4
   * - 3A2
     - Emisiones de CH4 del gestión de estiércol
     - CH4
   * - 3A2
     - N2O Emisiones directas de la gestión de estiércol
     - N2O
   * - 3C6
     - N2O Emisiones indirectas de la gestión de estiércol
     - N2O
   * - 3C2
     - Encalado: Emisiones anuales de CO2-C de Encalado
     - CO2
   * - 3C3
     - Fertilización de urea: Emisiones anuales de CO2
     - CO2
   * - 3C4
     - N2O Emisiones Directas de Suelos Agrícolas
     - N2O
   * - 3C5
     - N2O Emisiones Indirectas de Suelos Agrícolas
     - N2O
   * - 3C7
     - Emisiones de CH4 de la producción de arroz
     - CH4
   * - 3C1
     - Emisiones de la quema de biomasa en tierras de cultivo
     - CH4, N2O, NOx, CO

Emisiones
---------

.. list-table:: Tabla 2. Clasificación de emisiones estimadas en el modelo de agricultura
   :header-rows: 1

   * - Código
     - Descripción
   * - CO2e_GAN_FERM
     - Dióxido de carbono equivalente de fermentación entérica
   * - CO2e_GAN_GE
     - Dióxido de carbono equivalente de gestión de estiércol
   * - CO2e_GAN_GEI
     - Dióxido de carbono equivalente de gestión directa de estiércol
   * - CO2e_GAN_GED
     - Dióxido de carbono equivalente de gestión indirecta de estiércol
   * - CO2e_AGR_DIR
     - Dióxido de carbono equivalente de gestión directa de suelos agrícolas
   * - CO2e_AGR_IND
     - Dióxido de carbono equivalente de gestión indirecta de suelos agrícolas
   * - CO2e_ENC
     - Dióxido de carbono de encalado
   * - CO2e_URE
     - Dióxido de carbono de fertilización con urea
   * - CO2e_BIO
     - Dióxido de carbono equivalente por quema de biomasa
   * - CO2e_ARR
     - Dióxido de carbono equivalente de producción de arroz

Tecnologías
-----------

.. list-table:: Tabla 3. Tecnologías de productos agrícolas incluidas en el modelo de agricultura
   :header-rows: 1

   * - Descripción
     - Código
   * - Tierras de cultivo Arroz
     - AG_ARR
   * - Tierras de cultivo Banano
     - AG_BAN
   * - Tierras de cultivo Cacao
     - AG_COC
   * - Tierras de cultivo Café
     - AG_COF
   * - Tierras de cultivo Caña de azúcar
     - AG_SUG
   * - Tierras de cultivo Maíz
     - AG_MAI
   * - Tierras de cultivo Palma africana
     - AG_PAF
   * - Tierras de cultivo Soya
     - AG_SOY
   * - Tierras de cultivo Palmito
     - AG_PAL
   * - Tierras de cultivo Legumbres
     - AG_LEG
   * - Tierras de cultivo Cereales
     - AG_CER
   * - Tierras de cultivo Tubérculos
     - AG_TUB
   * - Tierras de cultivo Frutas
     - AG_FRT
   * - Tierras de cultivo Hortalizas
     - AG_VEG
   * - Tierras de cultivo Flores
     - AG_FLO

.. list-table:: Tabla 4. Tecnologías de productos ganaderos incluidas en el modelo de agricultura
   :header-rows: 1

   * - Descripción
     - Código
   * - Pasturas Bovinos
     - GA_BOV
   * - Pasturas Bovinos Vacas
     - GA_BOVVAC
   * - Pasturas Bovinos Crecimiento
     - GA_BOVCRE
   * - Pasturas Bovinos Leche
     - GA_BOVLEC
   * - Pasturas Bovinos Regenerativo
     - GA_BOVREG
   * - Pasturas Bovinos Vacas Regenerativo
     - GA_BOVVACREG
   * - Pasturas Bovinos Crecimiento Regenerativo
     - GA_BOVCREREG
   * - Pasturas Bovinos Leche Regenerativo
     - GA_BOVLECREG
   * - Pasturas Búfalos
     - GA_BUF
   * - Pasturas Ovejas
     - GA_OVE
   * - Pasturas Cabras
     - GA_CBR
   * - Pasturas Camélidos sudamericanos
     - GA_CAM
   * - Pasturas Caballos
     - GA_CAB
   * - Pasturas Mulas
     - GA_MUL
   * - Pasturas Cerdos
     - GA_POR
   * - Pasturas Aves
     - GA_AVE
   * - Pasturas Patos
     - GA_PAT
   * - Pasturas Pavos
     - GA_PAV
   * - Pasturas Ponedoras
     - GA_PON