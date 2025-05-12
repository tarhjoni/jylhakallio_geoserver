# 🌍 GeoServer Render Deploy

Tämä projekti on valmiiksi pakattu GeoServerin ajamiseen Render.com ilmaisessa palvelussa.

## 🚀 Käyttöönotto

1. Forkkaa tai kloonaa tämä repo omalle GitHub-tilillesi.
2. Luo Render-tili → https://render.com
3. Luo uusi **Web Service** Renderissa.
4. Valitse tämä GitHub-repository.
5. Render rakentaa automaattisesti Docker imagesta.
6. Aseta ympäristömuuttuja:
    - `PORT = 8080`
7. Odota deployn valmistumista → avaa URL:
    - `https://<palvelun_nimi>.onrender.com/geoserver`

## 💡 Huomioitavaa

- Tämä toimii Renderin ilmaisella tasolla → max. 512 MB RAM, 0.5 CPU
- Sopii testaukseen, ei raskaisiin tuotantoympäristöihin
- Render asettaa palvelun "sleep modeen", jos sitä ei käytetä 15 minuuttiin.

## 🔗 Lisätietoa

- [GeoServer Docker image](https://hub.docker.com/r/eclipse/geoserver)
- [Render Docs](https://render.com/docs)
