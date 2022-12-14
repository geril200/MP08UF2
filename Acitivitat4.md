# Activitat 4:

## Gestió d'usuaris:

Hi ha dos tipus d'usuaris, els admins amb permissos per gestionar Owncloud i els usuaris normals.

On fica resposta afegeix una captura de pantalla on es vegi que has fet l'acció que es demana.

**Aquesta part de la pràctica la feu amb un company/a, li creeu un usuari i li doneu el vostre nom de domini d'Owncloud.**

Per a que pugui accedir necessitarà:

- La MV amb owncloud ha d'estar en mode "adaptador pont".
- El fitxer /etc/hosts de µvla MV i el nom de domini de la MV del company/a.


**4.1.-** Crea un usuari admin que es digui adminXYZ, on XYZ són les inicials del teu nom:

![imatge](1b.png)
![imatge](2b.png)

**RESPOSTA**

**4.2.-** Inicia sessió com a l'usuari adminXYZ.

![imatge](3b.png)
![imatge](4b.png)

**RESPOSTA**

**4.3.-** Crea un usuari XYZ on XYZ son les inicials del company/a i afegeix-lo al grup usuaris, aquest usuari tindrà una quota de 512 MB.

![imatge](5b.png)
![imatge](6b.png)

**RESPOSTA**

**4.4.-** Podem crear fitxers d'una mida determinada a Linux amb la comanda:

```
truncate -s 10M file.txt
```

A l'exemple es crea un fitxer de 10MB.

Crea 6 fitxers de 100MB i pujal's a Owncloud un per un.

![imatge](7b.png)
![imatge](8b.png)
![imatge](9b.png)

**RESPOSTA**

**4.5.-** Mostra el missatge d'error per haver superat la quota d'usuari.

![imatge](10b.png)

**RESPOSTA**

**4.6.-** Busca al teu perfil quin percentatge de quota estas utilitzant.

**RESPOSTA**

**4.7.-** Canvia la quota de l'usuari a 1GB i mostra tots els fitxers pujats.

![imatge](11b.png)
![imatge](12b.png)

**RESPOSTA**

**4.8.-** Crea un usuari anomenat usuari2XYZ i fical al grup usuaris.

![imatge](13b.png)

**RESPOSTA**

**4.9.-** Comparteix un fitxer de usuariXYZ a usuari2XYZ i mostra com l'usuari2XYZ pot veure i descarregar el fitxer.

![imatge](14b.png)
![imatge](15b.png)

**RESPOSTA**

**4.10.-** Esborra la carpeta Learn more about owncloud.

![imatge](16b.png)
![imatge](17b.png)

**RESPOSTA**

**4.11.-** Recupera la carpeta Learn more about owncloud.

![imatge](18b.png)
![imatge](19b.png)
![imatge](20b.png)
![imatge](21b.png)

**RESPOSTA**

**4.12.-** Com a usuariXYZ crea una carpeta nova anomenada shared i comparteix-la amb l'usuari usuari2XYZ.

![imatge](22b.png)
![imatge](23b.png)

**RESPOSTA**

**4.13.-** Entra a Market instal·la dues aplicacions que no estiguin ja instal·lades i explica què fan i com funcionen.

- Contacts: Permet als usuaris sincronitzar i fer còpies de seguretat de les seves llibretes d'adreces amb ownCloud i en diversos dispositius. 

![imatge](24b.png)
![imatge](25b.png)
![imatge](26b.png)
![imatge](27b.png)

- Factor Authentication: Afegeix una altra capa de seguretat d'accés a ownCloud. El mètode d'autenticació confirma la identitat d'un usuari mitjançant una combinació de dos components independents.

![imatge](28b.png)
![imatge](29b.png)

![image](https://user-images.githubusercontent.com/110727546/196159706-705ff624-c409-4632-acb4-f43ffcc486d4.png)

**RESPOSTA PRIMERA APP**

**RESPOSTA SEGONA APP**

**4.14.-** Crearem una carpeta nova per emmagatzematge a Owncloud, la carpeta serà /media/publicXYZ on XYZ són les teves inicials i apareixerà amb el nom de public als usuaris.

![imatge](30b.png)
![imatge](31b.png)

Aquesta carpeta haurà de pertànyer a l'usuari www-data.

**RESPOSTA**

**4.15.-** Connectarem la carpeta publicXYZ com emmagatzematge local, tal i com s'indica [aquí](https://doc.owncloud.com/server/next/admin_manual/configuration/files/external_storage/local.html). Tots els usuaris tindran accés a la carpeta.

![imatge](32b.png)
![imatge](33b.png)

**RESPOSTA**

**4.16.-** Un usuari normal pujarà un fitxer a la carpeta public.

![imatge](34b.png)
![imatge](35b.png)
![imatge](37b.png)

**RESPOSTA**

**OPCIONAL.-** Aquesta tasca és opcional.

Intenta connectar com a emmagatzematge extern el teu compte de Google Drive de l'Institut. Tens com fer-ho aquí.

**RESPOSTA**


