# 01 – Active Directory

## Arquitectura
Configuré dos máquinas virtuales en VirtualBox sobre una red interna, para simular un entorno aislado:

- **SRV-DC01:** Windows Server 2025, IP estática **192.168.50.10**, dominio **srv.local**.
- **Cliente:** Windows 11 Enterprise, IP **192.168.50.20**, con el DNS apuntando al servidor.

<details>
<summary>Capturas</summary>

![Configuración del servidor en CMD](./Images/IP_HostN.png)
![Validación de comunicación del cliente](./Images/Cliente_W.png)

</details>

## Estructura
Separé a los usuarios en unidades organizativas para ordenarlos por función y facilitar la gestión de accesos.

En la unidad **Support_TI** creé la cuenta **f.ramos**, miembro del grupo **Domain Admins**.
