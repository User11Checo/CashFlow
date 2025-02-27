`# FlowCash Para la corecta instalacion del proyecto movil es nesesario la intalacion de las siguintes dependencias en su editor de codigo .

- "@react-navigation/native" - "@react-navigation/bottom-tabs" - "react-native-screens" - "react-native-safe-area-context" - "react-native-gesture-handler" - "react-native-reanimated" - "react-native-vector-icons" - "react-native-paper" - "react-native-linear-gradient"

#Que es FlowCash

Es el nombre de la aplicación que se está desarrollando a lo largo de este cuatrimestre, la idea principal es que el usuario tengo es registro de gastos y llevar un buen control de sus gastos, agregando gastos por categorías, analizar y deducir reportes mensuales y otorgar al usuario sugerencias de ahorro.

#Objetivo General

Desarrollar una aplicación móvil intuitiva y fácil de usar que permita a los usuarios registrar, organizar y analizar sus gastos personales de manera eficiente, proporcionando herramientas para gestionar su presupuesto, visualizar estadísticas y mejorar su control financiero.

##Descripcion de la APP

La aplicación "FlowCash" es una herramienta digital diseñada para ayudar a los usuarios a llevar un control detallado de sus finanzas personales. Permite registrar gastos en diferentes categorías, visualizar reportes y establecer presupuestos mensuales. Con una interfaz intuitiva, la app facilita el seguimiento de los gastos diarios, ofreciendo opciones como historial de transacciones, filtrado por categorías y generación de reportes.

###Funciones Principales


Registro de gastos con monto, categoría y fecha.
Visualización de gastos.
Establecimiento de un presupuesto mensual.
Interfaz minimalista
La aplicación es ideal para estudiantes, profesionales o cualquier persona interesada en mejorar su educación financiera y optimizar sus hábitos de gasto.

#Tipo de arquitectura

La arquitectura que se empleo en el proyecto es basade en modulos y navegacion con React Navigation, de esta forma se nos facilita la creacion de una interfaz simple y sencilla para el usuario.

#Framework Seleccionado

El framework que se seleccionó por su fácil uso es “React Native”, ya que su implementación es parecido a la de “Bootstrap”, ya que permite que los componentes sean dinámicos, de esta forma brindando una interfaz mas sencilla e intuitiva para el usuario final.

#Diagramas de flujo de la aplicacion

st=>start: 🏠 Inicio (Dashboard)
add_expense=>operation: ➕ Agregar Gasto
save_expense=>operation: 💾 Guardar Gasto
history=>operation: 📋 Historial de Gastos
reports=>operation: 📊 Reportes
settings=>operation: ⚙️ Configuración
back_home=>end: 🏠 Volver a Inicio

st->add_expense
st->history
st->reports
st->settings
add_expense->save_expense
save_expense->back_home
history->back_home
reports->back_home
settings->back_home
#Estrategia de versionaminto

En la modalidad de versionamiento se optara por una estrategia “SemVer”, ya que esta herramienta se piensa que sea un software estable, ya que no requerirá de muchas actualizaciones o de un desarrollo continuó, ya que los cambios más grandes que sufriría esta herramienta seria el precio de las monedas (si se llegara a implementar), pero eso se resolvería con el uso de una API, de esta manera las versiones del software se nombran con secuencias numéricas.

`
