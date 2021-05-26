# TrueNAS
TrueNAS / FreeNAS

### 2FA deaktivieren
Wenn man noch via SSH drauf kommt kann man so 2FA für die GUI deaktivieren.
midclt call auth.twofactor.update '{"enabled": false}'
