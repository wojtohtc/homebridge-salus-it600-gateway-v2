# Homebridge Salus iT600 Thermostat Gateway v2

**Improved and updated Homebridge plugin for Salus iT600 thermostats and UG600 gateway.**

This is a community-maintained fork of the original [homebridge-salus-it600-gateway](https://github.com/edlea/homebridge-salus-it600), focused on bugfixes, compatibility improvements, and future support for more device types.

---

## 🔧 Features

- Integration of Salus iT600 thermostats with Apple HomeKit via Homebridge
- Support for multiple thermostat models
- Remote temperature control and monitoring from the Home app
- Authentication with Salus Smart Home credentials

---

## 🚀 Installation

Install the plugin via npm:

```bash
npm install -g homebridge-salus-it600-gateway-v2
```

Add the platform to your Homebridge `config.json`:

```json
{
  "platforms": [
    {
      "platform": "Salus-iT600-v2",
      "username": "your_email@example.com",
      "password": "your_password",
      "thermostatModels": [
        "exampleModel1",
        "exampleModel2"
      ]
    }
  ]
}
```

> Use the same login credentials as for your Salus Smart Home account.

---

## 📌 Status

This project is in active maintenance and development.  
Feel free to submit issues or pull requests for improvements or device support.

---

## 📄 License

MIT
