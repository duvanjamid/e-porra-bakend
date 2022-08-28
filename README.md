# e-porra-bakend

## proyecto para el bakend el proyecto E-Porra de la Maestria MISO

```python
api = Api(app)
api.add_resource(VistaSignIn, '/signin')
api.add_resource(VistaLogIn, '/login')
api.add_resource(VistaCarrerasUsuario, '/usuario/<int:id_usuario>/carreras')
api.add_resource(VistaCarrera, '/carrera/<int:id_carrera>')
api.add_resource(VistaApuestas, '/apuestas')
api.add_resource(VistaApuesta, '/apuesta/<int:id_apuesta>')
api.add_resource(VistaTerminacionCarrera, '/carrera/<int:id_competidor>/terminacion')
api.add_resource(VistaReporte, '/carrera/<int:id_carrera>/reporte')

```
