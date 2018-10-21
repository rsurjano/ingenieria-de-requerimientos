## Modelo de casos de uso del negocio

[ ] seleccionar el proceso de negocio a modelar
[ ] seleccionar los 4 casos de uso del negocio (diagrama)
[ ] el producto tiene que ser medible/cuantitativo

- Actores de negocio: Stakeholders(dentro de la organizacion) & Cliente(fuera)

---
clase 02

---

cliente -> elaborar planos(ingeniero en jefe)
  ingeniero en jefe -> dibujar los planos(tecnicos especialistas) codigo, tipo, escala, fecha
  tecnicos especialistas -> establecer la informacion del terreno: ubicacion, calidad del terreno
  tecnicos especialistas -> enviar planos listos (ingeniero en jefe)
  ingeniero en jefe -> elaborar presupuesto de la obras
  ingniero en jefe -> presentar presupuesto(cliente)

cliente -> solicitar cambios en los planos (tecnicos especialistas)
  tecnicos especialistas => entregar version final al cliente


cliente -> planificar construccion
  ingeniero en jefe -> enviar la solicitud de permiso de construccion
  responsable de obras -> envia permiso de construccion, concedido, denegado total o parcial
    si es parcialmente denegado -> responsable de obras envia un informe de rechazo parcial
  ingeniero en jefe -> reenvia solicitud de permiso con planos modificados
    si es parcialmente denegado -> continuar hasta que se apruebe
    ingeniero, si es denegado totalmente -> encargar nuevos planos
  municiaplidad

un mismo plano se puede usar en muchas obras
