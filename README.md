
# NEYFFSYSTEMINFO   

Bir Windows Servisidir. Kaynak Kodları Priv Repo içindedir.

## API Kullanımı

#### Kaynak kullanımlarını JSON formatında döner

```http
  GET /api/SystemInfo
```

Örnek Response
```Response
{
    "status": 200,
    "message": "OK",
    "response": {
        "CpuKullanimiYuzdesi": {
            "ToplamKullanilanCpuYuzdesi": 2.65,
            "CekirdekSayisi": 16
        },
        "RamBilgisi": {
            "ToplamRamMB": 15554.36,
            "KullanilanRamMB": 11169.4,
            "BosRamMB": 4384.96,
            "KullanilanRamYuzdesi": 71.81,
            "BosRamYuzdesi": 28.19
        },
        "DiskBilgisi": [
            {
                "SurucuAdi": "C:\\",
                "ToplamAlanGB": 928.58,
                "BosAlanGB": 789.66,
                "KullanilanAlanGB": 138.93,
                "KullanilanAlanYuzdesi": 14.96,
                "BosAlanYuzdesi": 85.04
            },
            {
                "SurucuAdi": "D:\\",
                "ToplamAlanGB": 24.41,
                "BosAlanGB": 24.35,
                "KullanilanAlanGB": 0.06,
                "KullanilanAlanYuzdesi": 0.25,
                "BosAlanYuzdesi": 99.75
            }
        ]
    }
}
```

  
## Ekran Görüntüleri

![Uygulama Ekran Görüntüsü](https://i.imgur.com/HiX3IxM.jpeg)

  
