# Kilmer Bustos

Egresado de Ingeniería de Telecomunicaciones. Me interesa el lado defensivo de la seguridad — detección, análisis de amenazas, entender cómo funciona lo que intenta entrar.

La mayoría de lo que subo acá son proyectos que construí para aprender haciendo (hands-on-lab): infraestructura real, datos reales, problemas reales que tuve que resolver en el camino.

---

## Proyectos

### [cloud-honeynet-aws](https://github.com/killex007-pftw/cloud-honeynet-aws)
HoneyNet cloud-native desplegada en AWS. Tres honeypots (Cowrie, T-Pot CE, Dionaea) con un pipeline de Threat Intelligence automatizado contra AbuseIPDB, GreyNoise y OTX, y correlación centralizada en Wazuh con reglas custom mapeadas a MITRE ATT&CK.

En ~7 días de operación: 137,657 eventos capturados, 85 alertas TI, y tres hallazgos que no esperaba — incluyendo una botnet SSH capturada en sesión activa y una máquina hospitalaria propagando malware SMB desde hacía dos meses.

### [soc-wazuh-lab](https://github.com/killex007-pftw/soc-wazuh-lab)
Laboratorio SOC local con Wazuh. Detección de amenazas, reglas de correlación custom y simulación de ataques para entender cómo se comporta un SIEM ante distintos vectores.

---

## Stack habitual

```
Cloud:    AWS (EC2, VPC, Security Groups, SSM)
SIEM:     Wazuh · OpenSearch
Lenguajes: Python · Bash
Otros:    Docker · MITRE ATT&CK · AbuseIPDB · GreyNoise
```

---

Escribo sobre lo que voy haciendo en [Medium]([https://medium.com/@killex007](https://medium.com/@kilmbust)).  
Lima, Perú.
