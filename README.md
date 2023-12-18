# Taller de evaluación: seminario-ISE-2023-B1

En esta última clase de Ingeniería de Servidores se plantea un taller práctico que tiene como objetivo movilizar las competencias adquiridas durante el curso. En particular, el ejercicio consiste en escribir una carta de motivación donde nos postularemos como candidatos para una de las tres ofertas de trabajo enunciadas a continuación. El ejercicio consta de dos partes:

1. **Primera parte (candidatura):** Debereis seleccionar una de las tres ofertas de trabajo expuestas a continuación y escribir una carta de motivación siguiendo las instrucciones descritas más abajo. Disponeis de 20 minutos para escribir la carta.
2. **Segunda parte (evaluación):** Una vez enviada la carta de motivación debereis esperar a que el profesor habilite el formulario de evaluación. Se os serán asignadas tres cartas de tres compañeros de forma anónima y vuestro trabajo consiste en ordenar las cartas de mejor a peor según vuestro criterio. Disponeis de 20 minutos para evaluar los ejercicios de los compañeros.

**NOTA:** El ejercicio, y por tanto la nota, depende del ranking establecido por vosotros. Sed honestos. Cada trabajo será evaluado por tres personas. La nota mínima será de 4.5 y la máxima de 10 aunque el profesor se reserva el derecho a modificarla en caso de encontrar anomalías en la redacción. Puede seguir más abajo las instrucciones específicas.

## 1. Ofertas de trabajo
---
1. **Ingeniero de Sistemas Junior - Administración y Optimización de Infraestructuras**

- **Empresa:** TechSolutions Innovations
- **Ubicación:** Ciudad Metrópolis
- **Salario:** $80,000 - $90,000 al año
- **Referencia:** TSIS-ADM2023

Buscamos un Ingeniero de Sistemas Junior para unirse al equipo de administración de sistemas en TechSolutions Innovations. No se requiere experiencia previa pero si motivación y sólidos conocimientos en virtualización y certificaciones relevantes. Tu papel será diseñar, implementar y optimizar infraestructuras informáticas.

---

---
2. **Ingeniero DevOps - Desarrollo y Despliegue Continuo**

- **Empresa:** CloudInnovate Solutions
- **Ubicación:** Silicon Valley
- **Salario:** $90,000 - $110,000 al año
- **Referencia:** CIS-DEVOPS2023

Únete a CloudInnovate Solutions como Ingeniero DevOps. Buscamos experiencia en Docker, Kubernetes, Jenkins y certificaciones DevOps (por ejemplo, AWS Certified DevOps Engineer). Serás responsable del desarrollo y despliegue continuo de nuestros productos líderes en la industria.

---

---
3. **Administrador de Redes y Seguridad de Sistemas**

- **Empresa:** SecureTech Solutions
- **Ubicación:** CyberCity
- **Salario:** $75,000 - $95,000 al año
- **Referencia:** STS-SECNET2023

SecureTech Solutions busca un Administrador de Redes y Seguridad de Sistemas. Necesitamos experiencia en firewalls, VPN, IDS/IPS, y certificaciones en seguridad de redes (CompTIA Security+, Cisco CCNA Security). Tu misión será diseñar y mantener la infraestructura de red y seguridad de la empresa.

---

## 2. Instrucciones para enviar una carta de motivación

### 2.1 Anonimización de la solicitud

Este repositorio es público y, por lo tanto, es preferible anonimizar las contribuciones del alumnado. Para ello, cada uno de vosotros obtendrá un código hash de su nombre real y, además, seleccionará un seudónimo.

1. **Obtención de vuestro código hash**: Podeis obtener un código hash de vuestro nombre utilizando los siguientes comandos.

**En Linux y Mac:**
```
echo -n "Vuestro nombre real" | md5sum

```

**En PowerShell de Windows:**
```
echo -n "Vuestro nombre real" | Get-FileHash -Algorithm MD5
```

El aspecto del resultado será una serie de valores similares a:
```
6a6c9f114ad8908c6b4d43678c27ce46
```

**Como la código anterior es muy largo, para simplificar nuestro código seran solo las primeros 5 valores. Es decir, en el caso del ejemplo: `6a6c9`**

2. **Elección de seudónimo:** No proporcioneis en ningún momento vuestro nombre real en la carta de motivación. En su lugar, podeis elegir uno de estos dos seudónimos: "Carmen Mola" o "Rafael Luna".

### 2.2 Proceso de redacción y envío de la carta de motivación


- Puede hacer todo el proceso desde la web en que se encuentra.
- Cree un nuevo archivo dentro de la carpeta `cartas` llamado `<su_codigo_hash>.md` y redacte la carta de motivación para la oferta elegida. No olvide utilizar seudónimo.
- Haga un Pull Request (PR) para enviar su propuesta.

Cada propuesta será evaluada por tres compañeros. A su vez, usted evaluará tres propuestas. 

## 3. Evaluación de cartas de motivación

Espere instrucciones del profesor una vez haya enviado su carta de motivación. Para proceder con la evaluación de las cartas de sus compañeros [puede seguir este enlace](https://docs.google.com/spreadsheets/d/15kN9dRVdWs4Y2zVaqjeEW1LO0NQX3IH4dlF4KrP6quc/edit?usp=sharing)