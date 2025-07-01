# Zabbix Template: Mikrotik IPsec Peer Discovery via SNMP

## 🇷🇺 Описание на русском

Этот шаблон Zabbix предназначен для мониторинга IPsec peer'ов на устройствах Mikrotik с использованием SNMP. Он автоматически обнаруживает IPsec соединения и создает триггеры для контроля их доступности.

### Возможности:
- Автоматическое обнаружение IPsec peer;
- Создание элементов данных для каждого соединения;
- Генерация триггеров при недоступности peer;
- Поддержка динамических туннелей IPsec.

### Требования:
- Устройство Mikrotik с включенным SNMP;
- Доступ к SNMP OID, связанным с IPsec;
- Zabbix версии 7.0 или выше.

### Установка:
1. Импортируйте файл `zbx_export_templates.yaml` через веб-интерфейс Zabbix.
2. Назначьте шаблон нужному хосту Mikrotik.
3. Убедитесь, что SNMP работает корректно и Zabbix получает данные.

---

## 🇬🇧 English Description

This Zabbix template is intended for monitoring IPsec peers on Mikrotik devices using SNMP. It automatically discovers IPsec connections and creates triggers to monitor their availability.

### Features:
- Automatic discovery of IPsec peers;
- Creation of data items for each connection;
- Trigger generation on peer unavailability;
- Supports dynamic IPsec tunnels.

### Requirements:
- Mikrotik device with SNMP enabled;
- Access to SNMP OIDs related to IPsec;
- Zabbix version 7.0 or higher.

### Installation:
1. Import the `zbx_export_templates.yaml` file through the Zabbix web interface.
2. Attach the template to your Mikrotik host.
3. Ensure SNMP is properly configured and data is received by Zabbix.

---

## 📁 Файл шаблона

Файл `zabbix-mikrotik-ipsec-snmp.yaml` содержит экспорт шаблона Zabbix и должен быть импортирован в интерфейсе Zabbix.

---

## 🛠 Поддержка и улучшения

PR и предложения приветствуются! Если вы сталкиваетесь с проблемами или хотите внести улучшения — создайте issue или pull request.
