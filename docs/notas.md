
- Los imanes laterales dan error con x > 0.9, quitándolos funciona.
- Da buen resultado luego de cada cambio de parámetros y previo al plano x-b o simulación hacer **Close All** y **Clear** en Custom Geometry (primer tab izquierda abajo) 
- Es importante definir la Mesh de FEMM antes de guardar el modelo. Para ahcerlo hay que ir a la tab de Simulation, Mesh Control. Los siguientes valores parece que funcionan:
    - Mesh size: 500
    - Airgap factor: 10
    - PM factor: 10
    - Structural PDE: FEMM original


