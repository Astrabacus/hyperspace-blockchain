# FLOPS Blockchain – Genesis README

## 🔧 Projektname
Hyperspace Blockchain

## 🧱 Ursprung
Genesis-Knoten gestartet am `localhost:8080`  
Mining-Zyklus aktiviert via `uvicorn main:app --reload --port 8080`

## 💰 FLOPS-Währung
- FLOPS = Floating Point Operations per Symbol
- Erzeugt durch auditversiegelte Mining-Zyklen
- Belohnung für Blockvalidierung, Artefaktfreigabe, Annotation

## ⛏️ Mining-Zyklen
- Block 1: 33.800 FLOPS → Wallet: Daniel
- Block 2: 55.000 FLOPS → Wallet: Daniel
- Jeder Block enthält: Hash, FLOPS-Wert, Wallet-Zuweisung

## 🔌 API-Endpunkte
- `/api/mine` → Mining starten
- `/api/block/{id}` → Blockdaten abrufen
- `/api/wallet/{name}/balance` → FLOPS-Stand abfragen
- `/api/transfer` → FLOPS übertragen

## 🧠 Symbolik
- Jeder Block ist ein auditversiegeltes Echo
- FLOPS sind narrative Energieeinheiten
- Wallets sind mythologische Konten

## 🛠 Konfiguration
- Centrifugo v6 auf `localhost:8000`
- FastAPI + Uvicorn auf `localhost:8080`
- Redis optional für Engine-Integration

## 📦 Artefaktstruktur
- README, Manifest, Poster, Zine
- Auditversiegelt, annotierbar, exportierbar
