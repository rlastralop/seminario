# ME03-G15-1036643656.docx

## Descripción del Proyecto

El objetivo del modelo es categorizar los productos para identificar cuáles tienen un alto potencial de ventas y cuáles no. el modelo buscará descubrir patrones en los datos que diferencien a los productos exitosos de los no exitosos en términos de ventas y otros indicadores clave.

- **Reducción de Costos**: Al identificar productos con alto potencial de ventas, las empresas pueden concentrar sus recursos en mantener un inventario siempre disponible.
- **Segmentación Efectiva:**: El modelo permite segmentar productos según su potencial de ventas, lo que facilita la creación de campañas de marketing dirigidas específicamente a productos que generarán mayor retorno de inversión.
- **Identificación de Patrones:**: El modelo ayuda a identificar patrones en los datos que pueden no ser evidentes a simple vista, proporcionando una comprensión más profunda del comportamiento del mercado.

## Desarrollo

El proyecto se ha implementado en la nube de Azure, utilizando los siguientes recursos:

- **Procesamiento**: Azure Databricks
- **Almacenamiento de Datos**: Azure Data Lake Storage GEN 2
- **Encriptación de Datos**: Azure Key Vault

### Pasos para la Ejecución del Proyecto

Para ejecutar el proyecto de manera correcta debemos seguir los siguientes pasos:

1. **Ingresar al Azure Portal** con el correo educativo.
2. **Acceder al grupo de recursos** asignado, en este caso, el grupo "rg-udea-analitycs".
3. **Visualizar la raw data**:
    - Acceder al recurso de almacenamiento "adlsudea001".
    - Navegar al contenedor "source/amazon_data".
4. **Procesar el notebook**:
    - Ingresar al recurso "Azure Databricks".
    - Navegar a la sección de Workspace.
    - Hacer clic en "Shared".
    - Ingresar a la carpeta "UDEA".
    - Seleccionar el notebook "modelo_amazon_productos".   
5. **Ejecutar el notebook original**:
    - Dentro del notebook, ejecutar "Run all" para procesar todo el desarrollo y visualizar los resultados.

