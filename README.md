# JSON-Challenge-Vue

Aşağıdaki gibi bulunan JSON dosyasının;
```
	{
		"name": "",
		"id": "",
		"group": "SteelBlue",
		"type": null
	},
	{
		"name": "",
		"id": "",
		"group": "SteelBlue",
		"type": "assistant"
	}
```

Aşağıda belirtilen şeklinde veya benzer yapıda düzenlenmesi gerekiyor

```
	{
		"group": "SteelBlue",
		"student": [name, name]
		"assistant": "name"
	},
```

veya

```
	{
		"SteelBlue": {
			"student": [name, name]
			"assistant": "name"
		}
	}
```

Çalışma sonunda belirlenen fonsiyonlar çağırıldığında JSON verisinin düzenlenmiş haliyle çıktısının alınması gerekiyor.

Örneğin: ```getGroup("SteelBlue")``` fonsiyonu çağrıldığında çıktısının yukarıda belirtilen sonuçlardan birinin veya benzerinin olması gerekiyor.

**Not:** Çalışma sonucu için sadece filter ile seçilen grup üyelerinin filtrelenmesi değil. Tüm JSON objesinin düzenlenmesi gerekmekte.
