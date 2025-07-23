# EKAZA Zigbee 3CH FerTrato – Driver para Hubitat Elevation

Este é um driver personalizado para o módulo **EKAZA EKAC-T3093Z**, um **Mini Módulo Zigbee com 3 canais** independentes de relé. Desenvolvido especialmente para uso com a plataforma **Hubitat Elevation**, este driver permite controlar cada canal individualmente, com integração total à interface de automação do Hubitat.

---

## ✅ Funcionalidades

- Controle de **3 canais independentes** (`CH1`, `CH2`, `CH3`)
- Criação automática de **child devices**
- Comandos `on` / `off` para cada canal
- Comandos `refresh` e `initialize`
- Logs de debug ativáveis nas preferências
- Compatível com dashboards Hubitat

---

## 🛠️ Instalação

1. Acesse **Drivers Code** no Hubitat.
2. Clique em **New Driver**.
3. Cole o código do arquivo `.groovy` deste repositório.
4. Salve como: `EKAZA Zigbee 3CH FerTrato`
5. Vá até o dispositivo físico no Hubitat e aplique este driver.
6. Clique em `Initialize` ou `Save Preferences` para criar automaticamente os child devices (`CH1`, `CH2`, `CH3`).

---

## 📦 Exemplo de Uso

Você pode adicionar os child devices ao seu painel **Hubitat Dashboard** e controlá-los como interruptores independentes.

---

## 🔎 Observações

- O driver envia comandos Zigbee para os endpoints 1, 2 e 3.
- Caso o dispositivo passe a relatar status automaticamente, o driver poderá ser atualizado para receber e exibir esses relatórios.
- Projetado com base na estrutura padrão de drivers multi-endpoint do Hubitat.

---

## 📋 Modelo Compatível

- **EKAZA EKAC-T3093Z**
  - Zigbee 3.0
  - AC100~240V
  - 3x150W (LED máx)
  - Modelo impresso no módulo: `EKAC-T3093Z`

---

## 💡 Créditos

Driver criado por [FerTrato] com apoio de estrutura da comunidade Hubitat.

---
