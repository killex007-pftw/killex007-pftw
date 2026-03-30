<div align="center">

 [Español](#es) ·  [English](#en)

</div>

---

<a name="es"></a>

# Kilmer Bustos

Egresado de Ingeniería de Telecomunicaciones. Me interesa el lado defensivo de la seguridad — detección, análisis de amenazas, entender cómo funciona lo que intenta entrar.

La mayoría de lo que subo acá son proyectos que construí para aprender haciendo (hands-on): infraestructura real, datos reales, problemas reales que tuve que resolver en el camino.

---

## Proyectos

### [cloud-honeynet-aws](https://github.com/killex007-pftw/cloud-honeynet-aws)

HoneyNet cloud-native desplegada en AWS. Tres honeypots (Cowrie, T-Pot CE, Dionaea) con un pipeline de Threat Intelligence automatizado contra AbuseIPDB, GreyNoise y OTX, y correlación centralizada en Wazuh con reglas custom mapeadas a MITRE ATT&CK.

En ~7 días de operación con la infraestructura en su configuración final: 137,657 eventos capturados, 85 alertas TI confirmadas, y tres hallazgos que no esperaba — incluyendo una botnet SSH capturada en sesión activa y una máquina hospitalaria propagando malware SMB desde hacía dos meses.

### [blue-team-writeups](https://github.com/killex007-pftw/blue-team-writeups)

Documentación de casos reales de SOC — alertas, Incident Response, Threat Hunting y Malware Analysis — resueltos en LetsDefend y Hack The Box.

No es un dump de respuestas: cada writeup sigue una plantilla propia con el contexto del alerta, el análisis paso a paso y el veredicto justificado. Actualmente cubre alertas de inyección SQL, XSS, command injection e IDOR. La cobertura de HTB Blue Team está en camino.

### [soc-wazuh-lab](https://github.com/killex007-pftw/soc-wazuh-lab)

Laboratorio SOC local con Wazuh. Detección de amenazas, reglas de correlación custom y simulación de ataques para entender cómo se comporta un SIEM ante distintos vectores.

---

## Stack habitual
```
Cloud:      AWS (EC2, VPC, Security Groups, SSM)
SIEM:       Wazuh · OpenSearch
Lenguajes:  Python · Bash
Otros:      Docker · MITRE ATT&CK · AbuseIPDB · GreyNoise · OTX
```

---

Escribo sobre lo que voy haciendo en [Medium](https://medium.com/@kilmbust).  
Lima, Perú.

---
---

<a name="en"></a>

# Kilmer Bustos

Telecommunications Engineering graduate. I'm drawn to the defensive side of security — detection, threat analysis, understanding how things that try to get in actually work.

Most of what I upload here are projects I built to learn by doing: real infrastructure, real data, real problems I had to figure out along the way.

---

## Projects

### [cloud-honeynet-aws](https://github.com/killex007-pftw/cloud-honeynet-aws)

Cloud-native HoneyNet deployed on AWS. Three honeypots (Cowrie, T-Pot CE, Dionaea) feeding an automated Threat Intelligence pipeline against AbuseIPDB, GreyNoise, and OTX, with centralized correlation in Wazuh using custom rules mapped to MITRE ATT&CK.

In ~7 days of operation with the infrastructure in its final configuration: 137,657 events captured, 85 confirmed TI alerts, and three findings I didn't expect — including an SSH botnet caught mid-session and a hospital machine that had been spreading SMB malware for two months.

### [blue-team-writeups](https://github.com/killex007-pftw/blue-team-writeups)

Documentation of real SOC cases — alerts, Incident Response, Threat Hunting, and Malware Analysis — worked through on LetsDefend and Hack The Box.

Not an answer dump: each writeup follows a custom template with alert context, step-by-step analysis, and a justified verdict. Current coverage includes SQL injection, XSS, command injection, and IDOR alerts. HTB Blue Team writeups are in progress.

### [soc-wazuh-lab](https://github.com/killex007-pftw/soc-wazuh-lab)

Local SOC lab with Wazuh. Threat detection, custom correlation rules, and attack simulation to understand how a SIEM behaves against different attack vectors.

---

## Usual stack
```
Cloud:      AWS (EC2, VPC, Security Groups, SSM)
SIEM:       Wazuh · OpenSearch
Languages:  Python · Bash
Other:      Docker · MITRE ATT&CK · AbuseIPDB · GreyNoise · OTX
```

---

I write about what I'm building on [Medium](https://medium.com/@kilmbust).  
Lima, Perú.
