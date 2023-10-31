# KN05: Netzwerk / Sicherheit

## A. Diagram erstellen
#### Diagram als Bild:
<img src="images/1.png" style="width:700px;"/>

## B. Subnetz und privaten IP wählen
#### 1. Screenshot der Subnetzen, die die Namen:
<img src="images/2.png" style="width:900px;"/>

#### 2. Zwei definierte IPs für Web- und DB-Server/Instanz:
KN05 Subnet: 172.31.80.0/20 (Range: )
- Web-server: 172.31.83.119<br> 
- DB-Server: 172.31.83.131<br>

## C. Objekte und Instanzen erstellen
#### 1. Screenshot der Liste der Sicherheitsgruppe mit sprechenden Namen/Feldern:
<img src="images/3.png" style="width:900px;"/>

#### 2. Screenshot der Inbound-Regel für die DB-Sicherheitsgruppe:
<img src="images/4.png" style="width:900px;"/>

#### 3. Screenshot der Liste der Elastic IPs mit sprechenden Namen: 
<img src="images/5.png" style="width:900px;"/>

#### 4. Zeigen Sie, dass Sie nun alle drei Seiten aufrufen können (index.html, info.php und db.php): 
<img src="images/6.png" style="width:900px;"/>
<img src="images/7.png" style="width:900px;"/>
<img src="images/8.png" style="width:900px;"/>

#### 5. Screenshot der Liste der Instanzen, wenn beide Instanzen gestoppt sind. Das Feld deröffentlichen IP und der Status (gestoppt) müssen sichtbar sein: 
<img src="images/9.png" style="width:900px;"/>

#### 6. Screenshot der Details beider Instanzen, so dass die Subnet ID sichtbar ist:
<img src="images/10.png" style="width:900px;"/>
<img src="images/11.png" style="width:900px;"/>

#### 7. Laden Sie die aktualisierten Cloud-init Konfigurationen hoch in Git. Im Web-Konfig, sollte die IP angepasst sein:
[Cloud-init-web](web-config.yaml) <br>
[Cloud-init-db](db-config.yaml)


