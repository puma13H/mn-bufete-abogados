# Microservicios del Sistema

## Auth Service

Responsabilidad:

* Registro de usuarios
* Inicio de sesión
* JWT
* Recuperación de contraseña

Endpoints:

* POST /auth/register
* POST /auth/login
* POST /auth/recover

---

## User Service

Responsabilidad:

* Gestión de perfiles
* Gestión de usuarios

Endpoints:

* GET /users
* POST /users
* PUT /users/{id}
* DELETE /users/{id}

---

## Case Service

Responsabilidad:

* Gestión de casos legales

Endpoints:

* GET /cases
* POST /cases
* PUT /cases/{id}

---

## Appointment Service

Responsabilidad:

* Gestión de citas

Endpoints:

* POST /appointments
* GET /appointments

---

## Document Service

Responsabilidad:

* Gestión documental

Endpoints:

* POST /documents
* GET /documents

---

## Payment Service

Responsabilidad:

* Gestión de pagos

Endpoints:

* POST /payments
* GET /payments

---

## Notification Service

Responsabilidad:

* Correos electrónicos
* Notificaciones

---

## Audit Service

Responsabilidad:

* Registro de auditoría
* Trazabilidad de acciones
