# FASE 1: DIAGNÓSTICO Y FUNDAMENTOS - COMPLETADO ✓

**Fecha inicio:** Enero 2025
**Fecha cierre:** 24 Abril 2026
**Duración real:** 2 semanas
**Estado:** ✓ COMPLETO

---

## Ambiente de Laboratorio

### Máquinas Virtuales Configuradas

#### 1. Kali Linux
- **IP:** 192.168.100.4
- **RAM:** 8 GB
- **CPUs:** 4
- **Almacenamiento:** 80 GB SSD
- **Red:** NAT Network (SecurityLab)
- **Estado:** ✓ Operacional

**Herramientas instaladas:**
- nmap ✓
- wireshark ✓

---

#### 2. Ubuntu Server 22.04 LTS
- **IP:** 192.168.100.7
- **RAM:** 4 GB
- **CPUs:** 2
- **Almacenamiento:** 100 GB
- **Red:** NAT Network (SecurityLab)
- **Estado:** ✓ Operacional

**Software instalado:**
- Python 3.10.12 ✓
- Git ✓
- Docker ✓
- Python venv con: paramiko, requests, beautifulsoup4, scapy ✓
- Splunk 10.2.2 ✓

**SSH:** ssh redfalcon@192.168.100.7 ✓

---

#### 3. Metasploitable 3 - Linux
- **IP:** 192.168.100.X (DHCP)
- **RAM:** 2 GB
- **CPUs:** 2
- **Almacenamiento:** 30 GB
- **Red:** NAT Network (SecurityLab)
- **Estado:** ✓ Operacional

**Login:** msfadmin / msfadmin ✓

---

### Red de Laboratorio

**Tipo:** NAT Network (aislada)
- Nombre: SecurityLab
- Rango IPv4: 192.168.100.0/24
- DHCP: habilitado

---

## SIEM: Splunk Enterprise

- **Versión:** 10.2.2
- **Ubicación:** /opt/splunk
- **Acceso:** http://192.168.100.7:8000
- **Usuario:** splunk
- **Puerto:** 8000
- **Estado:** ✓ Corriendo
- **Boot-start:** Habilitado

---

## Logros Fase 1

✓ Lab aislado configurado (NAT Network)
✓ 3 VMs operacionales (Kali, Ubuntu, Metasploitable)
✓ Conectividad entre VMs verificada
✓ SIEM (Splunk) instalado y funcional
✓ SSH configurado (Kali ↔ Ubuntu)
✓ Python venv creado con dependencias
✓ Documentación generada

---

## Herramientas Disponibles

### Kali: nmap, wireshark, git, python3
### Ubuntu: Python 3 + venv, Docker, Git, Splunk
### Metasploitable: Servicios vulnerables para prácticas

---

## Próximos pasos (Fase 2)

**Semana 3-5:** Módulo A - Network Security
**Semana 6-8:** Módulo B - Incident Response
**Semana 9-10:** Módulo C - Vulnerabilidad
**Semana 11-12:** Módulo D - Compliance

---

**Documento generado:** 24 Abril 2026
**Estado:** Listo para Fase 2
