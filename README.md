# 🛠️ Laboratorio: Reparar un Servicio Dañado

Este repositorio contiene la evidencia técnica del laboratorio realizado como parte del módulo 34.4.1 del programa Generation. El objetivo principal fue diagnosticar y reparar un servicio dañado en un entorno controlado.

## 🧩 Objetivos del Laboratorio

- Identificar fallos en la configuración de un servicio.
- Aplicar técnicas de diagnóstico y reparación.
- Documentar el proceso paso a paso.
- Validar el funcionamiento del servicio tras la intervención.

## 🚀 Comandos utilizados

### 🔍 Verificar estado del servicio
```sudo systemctl status httpd```

### 🛠️ Editar configuración
```sudo vi /etc/httpd/conf/httpd.conf```

### 🧪 Probar configuració
```sudo apachectl configtest```

### 🔄 Reiniciar servicio
```sudo systemctl restart httpd```
