# KN01-Virtualisierung

### Host CPU Info:
Ctrl + shift + esc > open Perfomance Tab <br>
![alt text for screen readers](images/5-Gast-system_CPU-Info.png) <br>
Host CPU cores: 4 <br>
CPU: Central Processing Unit <br>
executes instructions of a computer program, such as arithmetic, logic, controlling, and input/output operations. 

### Konsolen-Ausgabe der CPUs bei weniger CPU als Gast-System:
![alt text for screen readers](images/1-weniger_CPU.png)

### Konsolen-Ausgabe der CPUs bei mehr CPU als Gast-System:
![alt text for screen readers](images/2-mehr_CPU.png)

### Host RAM Info:
Settings > System > About <br>
![alt text for screen readers](images/6-Gast-system_RAM-Info.png) <br>
Host RAM: 16.0 GB

### Konsolen-Ausgabe des RAM bei weniger RAM als Gast-System:
![alt text for screen readers](images/3-weniger_RAM.png)

### Fehlermeldung:
![alt text for screen readers](images/4-error_message.png)


### Warum die Fehlermeldung?

Der Gesamtspeicher der ausgeführten virtuellen Maschinen plus der Overhead für die VMware Server-Prozesse darf nicht größer sein als der physische Arbeitsspeicher des Hosts.
