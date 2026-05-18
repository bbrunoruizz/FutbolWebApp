 
FutbolWebApp - Navegación DataFlex

Ejercicio 5 - Eventos de navegación en orden

Al navegar hacia adelante (ej: SelectLiga ->> ZoomLiga):

1. OnGetNavigateForwardData - InvokingObject (botón que dispara la navegación)
2. OnNavigateForward - InvokedView (vista destino)
3. OnLoad - InvokedView
4. OnBeforeShow / OnShow - InvokedView

Al volver atrás:

5. OnGetNavigateBackData - InvokedObject
6. OnNavigateBack - InvokingObject (vista origen)
7. OnSaved / OnDelete - InvokedView (si hubo cambios)