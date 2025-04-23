
## **Manual técnico**

### **1. Resumen de direcciones IP y VLAN donde se justifique la elección de las máscaras de subred empleadas para las distintas subredes de las sedes y el *backbone*.**

---
### SUBNETING VLSM

### CUNDECH 

| RED        | No. De Host | ID de Red      | Máscara de Subred   | Primer Host Disponible | Último Host Disponible | Dirección de broadcast |
|------------|-------------|----------------|----------------------|-------------------------|-------------------------|------------------------|
| Biblioteca | 100         | 192.168.3.0/25 | 255.255.255.128      | 192.168.3.1             | 192.168.3.126           | 192.168.3.127          |
| Estudiantes| 50          | 192.168.3.128/26| 255.255.255.192     | 192.168.3.129           | 192.168.3.190           | 192.168.3.191          |
| Docentes   | 20          | 192.168.3.192/27| 255.255.255.224     | 192.168.3.193           | 192.168.3.222           | 192.168.3.223          |
| Seguridad  | 5           | 192.168.3.224/29| 255.255.255.248     | 192.168.3.225           | 192.168.3.230           | 192.168.3.231          |

---

### CUNOROC

| RED        | No. De Host | ID de Red      | Máscara de Subred   | Primer Host Disponible | Último Host Disponible | Dirección de broadcast |
|------------|-------------|----------------|----------------------|-------------------------|-------------------------|------------------------|
| Biblioteca | 75          | 192.148.3.0/25 | 255.255.255.128      | 192.148.3.1             | 192.148.3.126           | 192.148.3.127          |
| Estudiantes| 45          | 192.148.3.128/26| 255.255.255.192     | 192.148.3.129           | 192.148.3.190           | 192.148.3.191          |
| Docentes   | 25          | 192.148.3.192/27| 255.255.255.224     | 192.148.3.193           | 192.148.3.222           | 192.148.3.223          |
| Seguridad  | 10          | 192.148.3.224/28| 255.255.255.240     | 192.148.3.225           | 192.148.3.238           | 192.148.3.239          |

---

### CUNOC

| RED        | No. De Host | ID de Red       | Máscara de Subred   | Primer Host Disponible | Último Host Disponible | Dirección de broadcast |
|------------|-------------|------------------|----------------------|-------------------------|-------------------------|------------------------|
| Estudiantes| 60          | 172.16.3.0/26    | 255.255.255.192      | 172.16.3.1              | 172.16.3.62             | 172.16.3.63            |
| Biblioteca | 50          | 172.16.3.64/26   | 255.255.255.192      | 172.16.3.65             | 172.16.3.126            | 172.16.3.127           |
| Docentes   | 35          | 172.16.3.128/26  | 255.255.255.192      | 172.16.3.129            | 172.16.3.190            | 172.16.3.191           |
| Seguridad  | 5           | 172.16.3.192/29  | 255.255.255.248      | 172.16.3.193            | 172.16.3.198            | 172.16.3.199           |

---

### CUM

| RED        | No. De Host | ID de Red      | Máscara de Subred   | Primer Host Disponible | Último Host Disponible | Dirección de broadcast |
|------------|-------------|----------------|----------------------|-------------------------|-------------------------|------------------------|
| Biblioteca | 75          | 192.158.3.0/25 | 255.255.255.128      | 192.158.3.1             | 192.158.3.126           | 192.158.3.127          |
| Estudiantes| 45          | 192.158.3.128/26| 255.255.255.192     | 192.158.3.129           | 192.158.3.190           | 192.158.3.191          |
| Docentes   | 25          | 192.158.3.192/27| 255.255.255.224     | 192.158.3.193           | 192.158.3.222           | 192.158.3.223          |
| Seguridad  | 10          | 192.158.3.224/28| 255.255.255.240     | 192.158.3.225           | 192.158.3.238           | 192.158.3.239          |

---

### BACKBONE

| No. De Host | ID de Red     | Máscara de Subred | Primer Host Disponible | Último Host Disponible | Dirección de broadcast |
|-------------|----------------|--------------------|-------------------------|-------------------------|------------------------|
| 2           | 10.0.0.0/30    | 255.255.255.252    | 10.0.0.1                | 10.0.0.2                | 10.0.0.3               |
| 2           | 10.0.0.4/30    | 255.255.255.252    | 10.0.0.5                | 10.0.0.6                | 10.0.0.7               |
| 2           | 10.0.0.8/30    | 255.255.255.252    | 10.0.0.9                | 10.0.0.10               | 10.0.0.11              |
| 2           | 10.0.0.12/30   | 255.255.255.252    | 10.0.0.13               | 10.0.0.14               | 10.0.0.15              |
| 2           | 10.0.0.16/30   | 255.255.255.252    | 10.0.0.17               | 10.0.0.18               | 10.0.0.19              |
| 2           | 10.0.0.20/30   | 255.255.255.252    | 10.0.0.21               | 10.0.0.22               | 10.0.0.23              |
| 2           | 10.0.0.24/30   | 255.255.255.252    | 10.0.0.25               | 10.0.0.26               | 10.0.0.27              |
| 2           | 10.0.0.28/30   | 255.255.255.252    | 10.0.0.29               | 10.0.0.30               | 10.0.0.31              |
| 2           | 10.0.0.32/30   | 255.255.255.252    | 10.0.0.33               | 10.0.0.34               | 10.0.0.35              |
| 2           | 10.0.0.36/30   | 255.255.255.252    | 10.0.0.37               | 10.0.0.38               | 10.0.0.39              |

---


### IP Utilizadas

#### CUNDECH

| Equipo       | IP             |
|--------------|----------------|
| Seguridad2   | 192.168.3.226  |
| Biblioteca3  | 192.168.3.2    |
| Biblioteca4  | 192.168.3.3    |
| Estudiantes6 | 192.168.3.130  |
| Estudiantes7 | 192.168.3.131  |
| Docentes6    | 192.168.3.194  |
| Docentes7    | 192.168.3.195  |

---

#### CUNOROC

| Equipo       | IP             |
|--------------|----------------|
| Seguridad3   | 192.148.3.226  |
| Biblioteca1  | 192.148.3.2    |
| Estudiantes3 | 192.148.3.130  |
| Docentes3    | 192.148.3.194  |

---

#### CUNOC

| Equipo       | IP             |
|--------------|----------------|
| Docentes1    | 172.16.3.132   |
| Docentes2    | 172.16.3.133   |
| Seguridad4   | 172.16.3.196   |
| Estudiantes1 | 172.16.3.4     |
| Estudiantes2 | 172.16.3.5     |

---

#### CENTRAL

| Equipo     | IP             |
|------------|----------------|
| Servidor0  | 192.120.3.2    |
| Servidor1  | 192.121.3.2    |
| Servidor2  | 192.122.3.2    |

---

#### CUM

| Equipo       | IP             |
|--------------|----------------|
| Estudiantes5 | 192.158.3.132  |
| Docentes5    | 192.158.3.196  |
| Seguridad1   | 192.158.3.228  |
| Biblioteca2  | 192.158.3.4    |

---

### 2. Capturas de la implementación de las topologías


---

### 3. Detalle de todos los comandos utilizados

### Configuración CUNDECH

#### Protocolo VTP

```bash
# SW7
enable
conf t
vtp version 2
vtp domain Grupo3
vtp password usac2025
vtp mode server
exit

vlan 18
name Estudiantes

vlan 28
name Docentes

vlan 38
name Seguridad

vlan 48
name Biblioteca
```

```bash
# SW6
enable
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
exit
```

```bash
# SW8
enable
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
exit
```

---

#### Modo Trunk

```bash
# SW7
enable
conf t
int range fa0/1-3
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
```

```bash
# SW6
enable
conf t
int fa0/2
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
```

```bash
# SW8
enable
conf t
int fa0/2
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
```

---

#### Modo Access

```bash
# SW8
enable
config t
int fa0/3
switchport mode access
switchport access vlan 38
exit

int fa0/4
switchport mode access
switchport access vlan 48
exit

int fa0/5
switchport mode access
switchport access vlan 48
exit
```

```bash
# SW7
enable
config t
int range fa0/4-5
switchport mode access
switchport access vlan 18
exit
```

```bash
# SW8 (segunda sección)
enable
config t
int range fa0/3-4
switchport mode access
switchport access vlan 28
exit
```

---

#### Configuración MS8

```bash
enable
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025

interface vlan18
ip address 192.168.3.129 255.255.255.192
no shut
exit

interface vlan28
ip address 192.168.3.193 255.255.255.224
no shut
exit

interface vlan38
ip address 192.168.3.225 255.255.255.248
no shut
exit

interface vlan48
ip address 192.168.3.1 255.255.255.128
no shut
exit

int range fa0/1-3
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
```

---

```bash
# SW6
enable
conf t
int fa0/1
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
```

```bash
# SW8
enable
conf t
int fa0/1
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
```

---

### Configuración CUNOROC

#### Protocolo VTP

```bash
# SW3
enable
conf t
vtp version 2
vtp mode server
vtp domain Grupo3
vtp password usac2025
exit

vlan 18
name Estudiantes

vlan 28
name Docentes

vlan 38
name Seguridad

vlan 48
name Biblioteca
```

```bash
# SW4
enable
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
exit
```

```bash
# SW2
enable
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
exit
```

---

#### Modo Trunk

```bash
# SW3
enable
conf t
int range fa0/1
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit

int range fa0/3
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit
```

```bash
# SW4
enable
conf t
int fa0/1
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit
```

```bash
# SW2
enable
conf t
int fa0/2
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit
```

---

#### Modo Access

```bash
# SW3
int fa0/2
switchport mode access
switchport access vlan 18
exit
```

```bash
# SW4
int fa0/2
switchport mode access
switchport access vlan 38
exit

int fa0/3
switchport mode access
switchport access vlan 48
exit
```

```bash
# SW2
int fa0/3
switchport mode access
switchport access vlan 28
exit
```

---

#### Configuración R0

```bash
# SW2
enable 
conf t
int fa0/2
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
```

```bash
# R0
enable 
conf t
interface gi0/0.18
encapsulation dot1q 18
ip address 192.148.3.129 255.255.255.192
no shut
exit

interface gi0/0.28
encapsulation dot1q 28
ip address 192.148.3.193 255.255.255.224
no shut
exit

interface gi0/0.38
encapsulation dot1q 38
ip address 192.148.3.225 255.255.255.240
no shut
exit

interface gi0/0.48
encapsulation dot1q 48
ip address 192.148.3.1 255.255.255.128
no shut
exit

interface gi0/0
no shutdown
```

---


### Configuración CUNOC

#### Protocolo VTP y Modo Trunk en MS0

```bash
enable
conf t
vtp version 2
vtp mode server
vtp domain Grupo3
vtp password usac2025

vlan 18
name Estudiantes
exit

vlan 28
name Docentes
exit

vlan 38 
name Seguridad
exit

vlan 48
name Biblioteca 
exit

int range fa0/3-5
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
```

---

#### Configuración Clientes

```bash
# SW0 - VTP
enable
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
exit
```

```bash
# SW0 - Trunk
int fa0/1
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit

# SW0 - Access
int range fa0/2-3
switchport mode access
switchport access vlan 28
exit
```

```bash
# SW9 - VTP
enable
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
```

```bash
# SW9 - Trunk
int fa0/1
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit

# SW9 - Access
int fa0/2
switchport mode access
switchport access vlan 38
exit
```

```bash
# SW1 - VTP
enable
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
```

```bash
# SW1 - Trunk
int fa0/1
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit

# SW1 - Access
int range fa0/2-3
switchport mode access
switchport access vlan 18
exit
```

---

#### Redundancia

```bash
# MS1 - VTP
enable 
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
```

```bash
# MS2 - VTP
enable 
conf t
vtp version 2
vtp mode client
vtp domain Grupo3
vtp password usac2025
```

---

#### Protocolo HSRP

```bash
# MS1
int vlan 18
ip address 172.16.3.2 255.255.255.192
standby 1 ip 172.16.3.1
standby 1 priority 150
standby 1 preempt
no shut
exit

int vlan 28
ip address 172.16.3.130 255.255.255.192
standby 2 ip 172.16.3.129
standby 2 priority 150
standby 2 preempt
no shut
exit

int vlan 38
ip address 172.16.3.194 255.255.255.248
standby 3 ip 172.16.3.193
standby 3 priority 150
standby 3 preempt
no shut
exit

int vlan 48
ip address 172.16.3.66 255.255.255.192
standby 4 ip 172.16.3.65
standby 4 priority 150
standby 4 preempt
no shut
exit
exit
```

```bash
# MS2
int vlan 18
ip address 172.16.3.3 255.255.255.192
standby 1 ip 172.16.3.1
no shut
exit

int vlan 28
ip address 172.16.3.131 255.255.255.192
standby 2 ip 172.16.3.129
no shut
exit

int vlan 38
ip address 172.16.3.195 255.255.255.248
standby 3 ip 172.16.3.193
no shut
exit

int vlan 48
ip address 172.16.3.67 255.255.255.192
standby 4 ip 172.16.3.65
no shut
exit
exit
```

---

#### Modo Trunk en MS0, MS1 y MS2

```bash
# MS0
enable
conf t
int range fa0/1-2
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit
```

```bash
# MS1
enable
conf t
int fa0/2
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit
```

```bash
# MS2
enable
conf t
int fa0/2
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit
```

---

#### Enrutamiento en MS1 y MS2

```bash
enable
conf t
ip routing
exit
```

---

### Configuración CENTRAL

#### Protocolo VTP

```bash
# Switch0
enable
conf t
vtp version 2
vtp domain Grupo3
vtp password usac2025
vtp mode server
```

---

#### VLANs y Modo Access

```bash
vlan 58
name Server 0

vlan 68
name Server 1

vlan 78
name Server 2

int fa0/3
switchport mode access
switchport access vlan 68
exit

int fa0/2
switchport mode access
switchport access vlan 58
exit

int fa0/4
switchport mode access
switchport access vlan 78
exit
```

---

#### Modo Trunk

```bash
int fa0/1
switchport mode trunk
switchport trunk allowed vlan 58,68,78
```

---

#### Router on a Stick (R7)

```bash
# R7 - Subinterfaces
interface gi0/1.58
encapsulation dot1q 58
ip address 192.120.3.1 255.255.255.192
no shut
exit

interface gi0/1.68
encapsulation dot1q 68
ip address 192.121.3.1 255.255.255.192
no shut
exit

interface gi0/1.78
encapsulation dot1q 78
ip address 192.122.3.1 255.255.255.248
no shut
exit
```

---

### Configuración CUM

#### Protocolo VTP — SW5

```bash
enable
conf t
vtp version 2
vtp mode server
vtp domain Grupo3
vtp password usac2025
exit

vlan 18
name Estudiantes

vlan 28
name Docentes

vlan 38
name Seguridad

vlan 48
name Biblioteca
```

---

#### Modo Trunk — SW5

```bash
int range fa0/1-2
switchport mode trunk
switchport trunk allowed vlan 18,28,38,48
exit
```

---

#### Modo Access — SW5

```bash
int fa0/3
switchport mode access 
switchport access vlan 18
exit 

int fa0/4
switchport mode access 
switchport access vlan 28
exit 

int fa0/5
switchport mode access 
switchport access vlan 38
exit 

int fa0/6
switchport mode access 
switchport access vlan 48
exit 

```

---

#### Protocolo HSRP

```bash
# R4
enable
conf t
int gi0/1.18
encapsulation dot1q 18
ip address 192.158.3.130 255.255.255.192
standby 1 ip 192.158.3.129
standby 1 priority 150
standby 1 preempt
no shut
exit

int gi0/1.28
encapsulation dot1q 28
ip address 192.158.3.194 255.255.255.224
standby 2 ip 192.158.3.193
standby 2 priority 150
standby 2 preempt
no shut
exit

int gi0/1.38
encapsulation dot1q 38
ip address 192.158.3.226 255.255.255.240
standby 3 ip 192.158.3.225
standby 3 priority 150
standby 3 preempt
no shut
exit

int gi0/1.48
encapsulation dot1q 48
ip address 192.158.3.2 255.255.255.128
standby 4 ip 192.158.3.1
standby 4 priority 150
standby 4 preempt
no shut
exit

int gi0/1
no shut
```

```bash
# R5
enable
conf t
int gi0/1.18
encapsulation dot1q 18
ip address 192.158.3.131 255.255.255.192
standby 1 ip 192.158.3.129
no shut
exit

int gi0/1.28
encapsulation dot1q 28
ip address 192.158.3.195 255.255.255.224
standby 2 ip 192.158.3.193
no shut
exit

int gi0/1.38
encapsulation dot1q 38
ip address 192.158.3.227 255.255.255.240
standby 3 ip 192.158.3.225
no shut
exit

int gi0/1.48
encapsulation dot1q 48
ip address 192.158.3.3 255.255.255.128
standby 4 ip 192.158.3.1
no shut
exit

int gi0/1
no shut
```

---


### Configuración BACKBONE — Implementación RIP

#### Configuración RIP en MS1, MS2 y MS3

```bash
# MS1
enable
conf t
router rip
version 2
no auto-summary
network 10.0.0.0
network 172.16.3.0
exit
```

```bash
# MS2
enable
conf t
router rip
version 2
no auto-summary
network 10.0.0.0
network 172.16.3.0
exit
```

```bash
# MS3
enable
conf t
ip routing
router rip
version 2
no auto-summary
network 10.0.0.0
exit
```

---

#### Asignación de direcciones IP

```bash
# MS1
int fa0/1
no switchport
ip address 10.0.0.1 255.255.255.252
no shut
exit
```

```bash
# MS3
int fa0/1
no switchport
ip address 10.0.0.2 255.255.255.252
no shut
exit

int fa0/2
no switchport
ip address 10.0.0.6 255.255.255.252
no shut
exit

int fa0/3
no switchport
ip address 10.0.0.9 255.255.255.252
no shut
exit
```

```bash
# MS2
int fa0/1
no switchport
ip address 10.0.0.5 255.255.255.252
no shut
exit
```

---

#### Configuración RIP en R0, R1 y R2

```bash
# R0
enable
conf t
router rip
version 2
no auto-summary
network 10.0.0.0
network 192.148.3.0
exit
```

```bash
# R1
enable
conf t
router rip
version 2
no auto-summary
network 10.0.0.0
exit
```

```bash
# R2
enable
conf t
router rip
version 2
no auto-summary
network 10.0.0.0
exit
```

---

#### Interfaz IP en R0, R1, R2

```bash
# R1
int gi0/0
ip address 10.0.0.10 255.255.255.252
no shut
exit
```

```bash
# R0
int se0/0/0
ip address 10.0.0.13 255.255.255.252
no shut
exit

int se0/0/1
ip address 10.0.0.21 255.255.255.252
no shut
exit
```

```bash
# R1
int se0/0/0
ip address 10.0.0.14 255.255.255.252
no shut
exit

int se0/0/1
ip address 10.0.0.17 255.255.255.252
no shut
exit
```

```bash
# R2
int se0/0/0
ip address 10.0.0.22 255.255.255.252
no shut
exit

int se0/0/1
ip address 10.0.0.18 255.255.255.252
no shut
exit
```

---

### Configuración de RUTEO ESTÁTICO

#### Asignación de IP en Interfaces

```bash
# R7
enable
conf t
interface gi0/0
ip address 10.0.0.25 255.255.255.252
no shut
exit
```

```bash
# MS5
enable
conf t
interface fa0/7
no switchport
ip address 10.0.0.26 255.255.255.252
no shut
exit
```

---

#### Rutas Estáticas

```bash
# R7
enable
conf t
ip route 192.120.3.0 255.255.255.192 10.0.0.26
ip route 192.121.3.0 255.255.255.192 10.0.0.26
ip route 192.122.3.0 255.255.255.248 10.0.0.26
exit
```

```bash
# MS5
enable
conf t
ip route 192.120.3.0 255.255.255.192 10.0.0.25
ip route 192.121.3.0 255.255.255.192 10.0.0.25
ip route 192.122.3.0 255.255.255.248 10.0.0.25
exit
```

---

### Configuración EIGRP

#### MS7

```bash
router eigrp 100
network 10.0.0.42 0.0.0.3
network 10.0.0.45 0.0.0.3
network 10.0.0.61 0.0.0.3
no auto-summary
exit

router eigrp 100
redistribute ospf 1 metric 100000 100 255 1 1500
exit

router ospf 1
redistribute eigrp 100 subnets
exit
```

---

#### R9

```bash
enable
conf t
int gi0/0
ip address 10.0.0.62 255.255.255.252
no shut
exit

int gi0/1
ip address 10.0.0.65 255.255.255.252
no shut
exit

router eigrp 100
network 10.0.0.62 0.0.0.3
network 10.0.0.65 0.0.0.3
no auto-summary
exit
```

---

#### R10

```bash
enable
conf t
int gi0/0
ip address 10.0.0.66 255.255.255.252
no shut
exit

int gi0/1
ip address 10.0.0.69 255.255.255.252
no shut
exit

router eigrp 100
network 10.0.0.66 0.0.0.3
network 10.0.0.69 0.0.0.3
no auto-summary
exit
```

---

#### MS8

```bash
enable
conf t
int fa0/4
no switchport
ip address 10.0.0.70 255.255.255.252
no shut
exit

router eigrp 100
network 10.0.0.70 0.0.0.3
network 192.168.3.0 0.0.0.127
network 192.168.3.128 0.0.0.63 
network 192.168.3.192 0.0.0.31
network 192.168.3.224 0.0.0.7
no auto-summary
exit
```

---

#### R2 — Redistribución

```bash
enable
conf t
router rip
version 2
redistribute eigrp 1 metric 5
exit

router ospf 1
redistribute eigrp 100 subnets
exit
```

---


### Configuración OSPF

#### MS4

```bash
enable 
conf t
int range fa0/1-3
channel-group 1 mode active
exit

int range fa0/4-6
channel-group 4 mode passive
exit

int fa0/7
no switchport
ip address 10.0.0.34 255.255.255.252
no shut
exit

int port-channel 1
no switchport
ip address 10.0.0.37 255.255.255.252
no shut
exit

int port-channel 4
no switchport
ip address 10.0.0.50 255.255.255.252
no shut
exit

ip routing
router ospf 1
network 10.0.0.37 0.0.0.3 area 0
network 10.0.0.50 0.0.0.3 area 0
network 10.0.0.34 0.0.0.3 area 0
exit
```

---

#### MS5

```bash
enable
conf t
int range fa0/1-3
channel-group 1 mode passive
exit

int range fa0/4-6
channel-group 2 mode active
exit 

int port-channel 1
no switchport
ip address 10.0.0.38 255.255.255.252
exit

int port-channel 2
no switchport
ip address 10.0.0.41 255.255.255.252
no shut
exit

router ospf 1
network 10.0.0.38 0.0.0.3 area 0
network 10.0.0.41 0.0.0.3 area 0
network 10.0.0.26 0.0.0.3 area 0
exit
```

---

#### MS7

```bash
enable
conf t
int range fa0/1-3
channel-group 2 mode passive
exit

int range fa0/4-6
channel-group 3 mode active
exit

int port-channel 2
no switchport
ip address 10.0.0.42 255.255.255.252
no shut
exit

int port-channel 3
no switchport
ip address 10.0.0.45 255.255.255.252
no shut
exit

int fa0/7
no switchport
ip address 10.0.0.61 255.255.255.252
no shut
exit

ip routing
router ospf 1
network 10.0.0.42 0.0.0.3 area 0
network 10.0.0.45 0.0.0.3 area 0
network 10.0.0.61 0.0.0.3 area 0
exit
```

---

#### MS6

```bash
enable
conf t
int range fa0/4-6
channel-group 3 mode passive
exit

int range fa0/1-3
channel-group 4 mode active
exit

int port-channel 3
no switchport
ip address 10.0.0.46 255.255.255.252
no shut
exit

int port-channel 4
no switchport
ip address 10.0.0.49 255.255.255.252
no shut
exit

int fa0/7
no switchport
ip address 10.0.0.54 255.255.255.252
no shut
exit

int fa0/8
no switchport
ip address 10.0.0.58 255.255.255.252
no shut
exit

ip routing
router ospf 1
network 10.0.0.46 0.0.0.3 area 0
network 10.0.0.49 0.0.0.3 area 0
network 10.0.0.54 0.0.0.3 area 0
network 10.0.0.58 0.0.0.3 area 0
exit
```

---

#### R2

```bash
enable
conf t
int gi0/0
ip address 10.0.0.29 255.255.255.252
no shut
exit

router ospf 1
network 10.0.0.29 0.0.0.3 area 0
network 10.0.0.22 0.0.0.3 area 0
network 10.0.0.18 0.0.0.3 area 0
exit

router ospf 1
redistribute rip subnets
exit

router rip
version 2
redistribute ospf 1 metric 5
exit
```

---

#### R3

```bash
conf t
int gi0/1
ip address 10.0.0.30 255.255.255.252
no shut
exit

int gi0/0
ip address 10.0.0.33 255.255.255.252
no shut
exit

router ospf 1
network 10.0.0.33 0.0.0.3 area 0
network 10.0.0.30 0.0.0.3 area 0
exit
```

---

#### R4

```bash
enable
conf t
int gi0/0
ip address 10.0.0.53 255.255.255.252
no shut
exit

router ospf 1
network 10.0.0.53 0.0.0.3 area 0
network 192.158.3.0 0.0.0.127 area 0    
network 192.158.3.128 0.0.0.63 area 0   
network 192.158.3.192 0.0.0.31 area 0  
network 192.158.3.224 0.0.0.15 area 0
exit
```

---

#### R5

```bash
enable
conf t
int gi0/0
ip address 10.0.0.57 255.255.255.252
no shut
exit

router ospf 1
network 10.0.0.57 0.0.0.3 area 0
network 192.158.3.0 0.0.0.127 area 0    
network 192.158.3.128 0.0.0.63 area 0   
network 192.158.3.192 0.0.0.31 area 0  
network 192.158.3.224 0.0.0.15 area 0
exit
```

---
