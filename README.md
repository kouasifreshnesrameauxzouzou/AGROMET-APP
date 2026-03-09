# 📻 RBM – Réseau Billital Maroobé

Application Streamlit de diffusion d'annonces audio pastorales et météorologiques multilingues.

## 🚀 Lancement

```bash
pip install streamlit
streamlit run app.py
```

## 🌍 Langues disponibles
| Langue   | Couleur  |
|----------|----------|
| Français | 🔵 Bleu   |
| Baoulé   | 🟢 Vert   |
| Bété     | 🟠 Orange |
| Dioula   | 🟣 Violet |

## 🔐 Accès Admin
- Menu ☰ → Admin
- Mot de passe par défaut : `rbm2026` (à changer dans `app.py`)

## ⚙️ Configuration
Dans `app.py`, modifier :
- `ADMIN_PASSWORD` — mot de passe administrateur
- `wa_number` — numéro WhatsApp de l'admin (format international sans +)

## 📁 Structure
```
rbm_app/
├── app.py                  # Application principale
├── requirements.txt
├── announcements.json      # Métadonnées (auto-généré)
└── audio_files/            # Fichiers audio (auto-généré)
```
