# Exemples d’utilisation

## Cas 1 : Dispatch de logs
```
python dispatcher.py --input logs/ --rule error_keywords --output archive/
```

## Cas 2 : Backup rapide vers stockage local
```
./dispatch.sh -i /mnt/data/ -t backup --dest ~/vault/
```

## Cas 3 : Préparation automatique pour analyse
```
deepvault --prepare-forensics --target /evidence --output /analysis-ready
```