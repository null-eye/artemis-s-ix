
[![Build](https://img.shields.io/badge/Artemiz%20-Series%20IX%20-orange?style=for-the-badge&logo=github)]()
[![Build](https://img.shields.io/badge/null%20eye%20-black?style=flat-square&label=author&logo=github)]()
 [![Build](https://img.shields.io/badge/version-4.0.0%20-success?style=flat&logo)]()

<h2>Information</h2>
Start Automation using Artemis<br>

<h3>Modules:</h3>

**Modules on version 4.0.0:**

| Modules           | Type    | Information                                       |Status  |
|  ---------------- | ------  |---------------------------------------------------|--------|
| arkspider-xss-test   |enumeration|Enumerate parameter and try with xss payloads      |stable  |
| uriel-admin-finder| scanner |Find admin login page using payloads               |stable  |
| uriel-bypass-admin | attacker|Attack admin login page using bypass admin payloads|stable  |

<h3>Installation & Usage</h3>

Step 1:

```
git clone https://github.com/null-eye/artemis-s-ix
```

Step 2:

```
bash artemis
```

Step 3:
```
set domain https://example.com
```

Step 4:
```
runtag uriel-admin finder
```
or
```
runtag scanner
```

<h3>More Information</h3>


Just type ` help ` in command line after entering , for more example:

```
  - help                                   Show this information
  - runtag <module.name>/<module.tag>      Running modules with single target
  - set domain <target>                    Setting the domain
  - show options/options                   Show all options and values
```


<br>

> **NOTE:** you can type `help` for more information




