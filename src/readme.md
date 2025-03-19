# Examen Test Unitario

## Test Unitario Parametrizado
- Generé los Test clicando en el botón derecho. 
 > Go To > Test > Create New Test
    -Le doy un nombre y selecciono el método que quiero comprobar.

- @ParameterizedTest para que el test se compruebe varias veces con distintos datos.
- @CsvSource para pasarle los datos que queremos que compruebe
- Al inicio me daba error en CalcularLetraTest me daba error.
- Actualmente sin yo cambiar nada, solo añadiendo más opciones (no preguntes como) los test pasan en ambos métodos
## Cambios de test si no hay comprobacion string.
- Habría que añadir más casos (más de 8 dígitos, menos de 8 dígitos, caracteres no numericos)