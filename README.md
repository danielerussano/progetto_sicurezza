# Progetto sicurezza informatica
L'applicativo preso in considerazione per questo progetto è un CRM (Customer Relationship Management).
Sono state scoperte vulnerabilità di tipo XSS e SQL Injection, e cercheremo di sfruttarle e fixarle.

Link al progetto originale: https://phpgurukul.com/small-crm-php/

La vulnerabilità SQL Injection si trova nel form di login che permette ad un utente non autenticato di entrare nella piattaforma come admin.\
La vulnerabilità XSS invece si trova nel form per l'inserimento di un nuovo ticket di supporto nella piattaforma.

Per l'utilizzo dell'applicativo si utilizzerà un ambiente con PHP + MySQLprogetto_sicurezza
