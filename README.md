# Qogir-Dark-Smoke

Variante **“Smoke”** del tema [Qogir](https://github.com/vinceliuice/Qogir-theme) (GTK3/GTK4/GTK2, Kvantum y rofi), con paleta oscura personalizada y variante compacta.

## Contenido

| Componente | Descripción |
|---|---|
| `Qogir-Dark-Smoke` | Tema GTK2/GTK3/GTK4 con paleta Smoke |
| `Qogir-Dark-Smoke-Compact` | Variante compacta (headerbars, pestañas, sliders y widgets más pequeños) |
| `Kvantum/Qogir-dark-Smoke` | Tema Kvantum (Qt/KDE) a juego |
| `Kvantum/Qogir-dark-Smoke-Compact` | Variante Kvantum compacta (menús sólidos) |
| `rofi/rounded-smoke-dark.rasi` | Tema de rofi a juego (autónomo) |
| `rofi/template/rounded-template.rasi` | Plantilla base de [newmanls](https://github.com/newmanls/rofi-themes-collection) (referencia) |

## Instalación

```bash
# GTK (GTK2/GTK3/GTK4)
cp -r Qogir-Dark-Smoke Qogir-Dark-Smoke-Compact ~/.themes/

# Kvantum (Qt/KDE)
cp -r Kvantum/Qogir-dark-Smoke Kvantum/Qogir-dark-Smoke-Compact ~/.config/Kvantum/

# rofi
mkdir -p ~/.local/share/rofi/themes
cp rofi/rounded-smoke-dark.rasi ~/.local/share/rofi/themes/
```

Luego:

- **GTK**: activar `Qogir-Dark-Smoke` (o `Qogir-Dark-Smoke-Compact`) en Apariencia / `gsettings set org.gnome.desktop.interface gtk-theme "Qogir-Dark-Smoke-Compact"`.
- **Kvantum (Qt/KDE)**: `Kvantum Manager` > *Select a Theme* > `Qogir-dark-Smoke-Compact`.
- **rofi**: en `~/.config/rofi/config.rasi` (o `drun.rasi`/`run.rasi`) poner `@theme "rounded-smoke-dark"`.

## Créditos

- [vinceliuice/Qogir-theme](https://github.com/vinceliuice/Qogir-theme) — tema base (GPL-3.0).
- [newmanls/rofi-themes-collection](https://github.com/newmanls/rofi-themes-collection) `rounded-template.rasi` — plantilla rofi de referencia.

Tema distribuido bajo [GPL-3.0](https://github.com/vinceliuice/Qogir-theme/blob/master/LICENSE).