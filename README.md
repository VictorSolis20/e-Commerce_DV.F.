# e-Commerce DV.F

Este es un proyecto de Ecommerce desarrollado en React, una aplicación web de una sola página (SPA) que permite a los usuarios explorar, buscar y comprar productos en línea. El objetivo principal de este proyecto es proporcionar una experiencia de compra fluida y agradable a través de una interfaz intuitiva y de fácil navegación.

- - -
### Características principales
- SPA (Single Page Application): La aplicación utiliza el enfoque SPA para proporcionar una experiencia de usuario sin interrupciones y una navegación fluida, reduciendo la necesidad de recargar la página en cada interacción.
- Rutas: Se ha implementado un sistema de enrutamiento que permite la transición entre diferentes vistas de la aplicación de manera eficiente. Las rutas están configuradas para garantizar una experiencia de usuario fluida y amigable.
- Rutas Privadas y Públicas: Se han implementado rutas privadas y públicas para mejorar la seguridad de la aplicación y restringir ciertas páginas solo a usuarios autenticados. El componente createBrowserRouter y RouterPriver se encargan de administrar el enrutamiento, mientras que useParams y useLocation se utilizan en productDetail.jsx para acceder a los datos de productos y proporcionar una funcionalidad de búsqueda optimizada con el uso del hook SWR (Stale-While-Revalidate).
- Context: Para gestionar el estado global de la aplicación y facilitar la comunicación entre componentes, se ha utilizado el contexto de React. Esto permite una administración más sencilla de datos compartidos y la actualización de componentes de manera eficiente.
- Reducer: Para mantener la lógica de manejo del estado de la aplicación organizada y escalable, se ha utilizado un patrón de Reducer. Esto permite administrar acciones y cambios de estado de manera predecible y fácil de mantener.

- - -
### Dependencias principales
- React: La biblioteca principal utilizada para construir la interfaz de usuario y gestionar los componentes de la aplicación.
- SWR: Una biblioteca que proporciona una gestión inteligente de caché y solicitudes de datos en tiempo real para optimizar el rendimiento de la aplicación.