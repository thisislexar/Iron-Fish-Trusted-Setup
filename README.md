<h1 align="center">Iron Fish Trusted Setup Kurulum Rehberi

## Iron Fish Trusted Setup kurulum rehberi. Sağ üstten yıldızlayıp forklamayı unutmayalım. Sorularınız olursa: [LossNode Chat](https://t.me/LossNode)

![image](https://user-images.githubusercontent.com/101462877/218675650-4db543b5-b68a-48fc-b44d-f4f52db49c38.png)



## Sistem gereksinimleri:
Tip | Gereksinimler    |
| ------------- |  -------- |
| Trusted Setup | Baya düşük, herhangi bir sunucunun yanına kurulur  |

## Iron Fish için önemli linkler:
- [Website](https://www.ironfish.network/)
- [Orijinal Doküman](https://www.ironfish.network/blog/2023/02/13/trusted-setup-ceremony?utm_content=buffer1c4e6&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
- [Twitter](https://twitter.com/ironfishcrypto)
- [Discord](https://discord.gg/MuWWfeesxZ)

# 1) Başlayalım kuruluma. Gerekli kütüphane vs. kurulumları yapıyoruz.

```
sudo apt-get update
```
```
sudo apt update && sudo apt upgrade -y
sudo apt install curl wget gnupg2
```
```
sudo apt install screen -y
```
```
sudo apt install npm -y
```

# Screen açalım ve devam.

```
screen -S ironfish
```

```
curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
```
```
sudo apt install nodejs -y
```
```
npm install -g ironfish
```
## Ironfish versiyonunu kontrol ediyoruz, 0.1.65'in üzerinde olduğuna emin olalım.
```
ironfish --version
```
![image](https://user-images.githubusercontent.com/101462877/218679789-32183cfa-65ce-4a3b-a482-840ea05b0b5f.png)

## Ironfish ceremony komutunu giriyoruz. İsterseniz random bir şey girin isterseniz Enter basın geçin.
```
ironfish ceremony
```
![image](https://user-images.githubusercontent.com/101462877/218680110-7b0f055d-4367-43b8-bd6c-0c9f5512c2c6.png)

## İsim ile mi contribute etmek istersin yoksa anonim mi diye soruyor, size kalmış.

![image](https://user-images.githubusercontent.com/101462877/218680299-c4f549ab-43b2-46e0-b8dd-4f6655f411f5.png)

## Bize contribute etmek için sıra verdi, screen'den Ctrl + A + D yaparak çıkıyoruz ve ara ara sıranın gelip gelmediğini kontrol ediyoruz.

![image](https://user-images.githubusercontent.com/101462877/218680575-ba17e34b-643c-42a4-98e1-5abe2442f6e4.png)

## Sıra bize geldikten sonra kendisi contribution yapacak, hash'i bir yere kaydedin.

![image](https://user-images.githubusercontent.com/101462877/218681267-d3d8177a-5307-4d50-9afc-89ebf781d78f.png)



# Sorularınız ve merak ettikleriniz için: [LossNode](https://t.me/LossNode)
