# Recipe Management - Helm
Dieser Helm Chart beinhaltet die konfigurierbaren Kubernetes Manifeste zur Recipe Management App.\
Dieses Repository beinhaltet eine beispielhafte Konfiguration in `recipe-management/values.yaml`, mit der einen lokaler Ingress auf den Hostnamen `localhost` konfiguriert.\
Installiert werden kann das Chart mit diesem Befehl:
```bash
helm install recipe-management-app ./recipe-management --values ./recipe-management/values.yaml
```
Änderungen können mit diesem Befehl angewendet werden:
```bash
helm upgrade recipe-management-app ./recipe-management --values ./recipe-management/values.yaml
```
Um das Projekt zu entfernen, kann dieser Befehl verwendet werden:
```bash
helm uninstall recipe-management-app
```
Der Standardnutzer lautet `user1` mit Passwort `password`.
