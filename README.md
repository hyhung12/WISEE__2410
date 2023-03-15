# WISEE__2410

- IP66, ISO 10816, two 3.6 batteries, 8 pre-calculated vibration features
- Device EUI, AppKey, AppEUI
- Class A (battery power, downlink avaialable after TX)
- 8 features each axis -> 24 features
- ISO 10816-3: mechanical vibraion on non-roating part
- ISO 10816: freqency (1kHz), vibration velocity RMS, evaluation zone, able to connect to cloud
- Raw data (g value) collected in spatial domain -> converted to vibration amplitude in freq domain with FFT -> abnomaly detection
- Sampling rate: 3200Hz, 2048 data on each axis
- 4 main features: velocity RMS, acceleration RMS, acceleration peak RMS, and displacement RMS


# WISEE__4610
- Lora : radio modulation technology  ≠ LoraWAN: protocol
- **OTAA** (over-the-air-activation): DevEUI, AppEUI, AppKey  ≠ **ABP** (activation by personalization): DevAddr, NwkSkey, AppSkey
- Rechargeable with 10-50V power supply and switch on
- Support LoRaWAN and WISE-LINK(LoRa Private) -> use gateway **WISE-3610**
- **S614** for AI data and **S672**; app-argument -> **WISE-S672**

# WISEE__6610
