# Micro_services-ACRIVITY3
# Partie Spring
## Partie 1
###Configuration Repo
![image](https://user-images.githubusercontent.com/76247057/209464339-6acaf465-4bce-4a10-bd9d-51020ddde75f.png)
### Config-Service 
![image](https://user-images.githubusercontent.com/76247057/209464420-391e21b5-5b50-475f-b8f8-6cc35c426edc.png)

### Customer-Service
![image](https://user-images.githubusercontent.com/76247057/209464436-47d24c51-d7f1-4a34-a00a-0058fdc5bc62.png)
![image](https://user-images.githubusercontent.com/76247057/209464446-f46ad2f6-5a4f-469b-afe6-3bbf0acf5e09.png)

### Inventory-Service 
les mêmes Dépendance que Customer service
### Order service 
les mêmes Dépendance que Customer service
### Gateway
![image](https://user-images.githubusercontent.com/76247057/209464521-7c532237-3437-4076-8977-cc73f82e4de6.png)
#### Dossier de configuration 
![image](https://user-images.githubusercontent.com/76247057/209464543-6a274d2b-4af6-4d08-824e-de55031f56a3.png)
#### la Configuration de Customer-Service via Consul config
![image](https://user-images.githubusercontent.com/76247057/209464584-d4fa2085-e364-4ed8-a6a5-eb8faded85db.png)
#### Pour dev 
![image](https://user-images.githubusercontent.com/76247057/209464608-27c54e7f-acda-42ba-a57d-eefb78520fc4.png)

#### Recuperation des properties par custoomer-service
![image](https://user-images.githubusercontent.com/76247057/209464644-4cc004b4-69e1-41db-b298-7feb94fb09c9.png)
#### Si On change la config
![image](https://user-images.githubusercontent.com/76247057/209464666-5c48660f-fa40-41bd-95c4-c26edc3abb46.png)
#####Actuliser la configuration avec actuator 
#####Demander a customer service de se refrechir
#####Configuration à chaud 
![image](https://user-images.githubusercontent.com/76247057/209464698-7252670e-8b06-47e4-a16a-820aeeb412c3.png)
####Spring data Rest 
![image](https://user-images.githubusercontent.com/76247057/209464735-b5fd1a7c-76a4-45e0-b622-ab30377aece2.png)
#### Tester la gateway 
![image](https://user-images.githubusercontent.com/76247057/209464760-db143018-d837-4393-89c3-2d2daf587121.png)
## Partie 2 
#### En utilisant les projections 
![image](https://user-images.githubusercontent.com/76247057/209464801-605c1b8b-a42f-4a33-bd26-98b5b519f787.png)
### Order-Service 
##### Voir customer est null car il est transient
![image](https://user-images.githubusercontent.com/76247057/209464830-924be33e-878a-4443-a62b-78cdf4e229ed.png)
![image](https://user-images.githubusercontent.com/76247057/209464840-965d4965-e522-433f-b4b4-cf344fdac16c.png)
### Consul
![image](https://user-images.githubusercontent.com/76247057/209464860-6149342f-9f93-4460-ac8c-d64afe8ab623.png)
### Vault
### Billing service
![image](https://user-images.githubusercontent.com/76247057/209464915-1749c27e-6500-4881-93fa-4136371f2222.png)
#### creer le dossier config 
![image](https://user-images.githubusercontent.com/76247057/209464938-4fa74dee-3229-48e2-bc12-4f4b2b05d581.png)
#### List de proprieties
![image](https://user-images.githubusercontent.com/76247057/209464966-6faebfdd-ad8d-4eff-9204-d6397d62c0ee.png)
###Vault
![image](https://user-images.githubusercontent.com/76247057/209464977-b85444aa-938d-41ec-b8ba-8183be222fea.png)
![image](https://user-images.githubusercontent.com/76247057/209464982-945bb0d7-0178-45ae-8432-64330f440cd9.png)
![image](https://user-images.githubusercontent.com/76247057/209464989-73cb5a55-929b-470b-bca6-1438cf4304d3.png)
# Partie Angular
#### List Product

![image](https://user-images.githubusercontent.com/76247057/209465054-81210414-64c6-4644-a216-1f45b951d2e8.png)
#### List Customer
![image](https://user-images.githubusercontent.com/76247057/209465087-ac184cbf-9b9e-4d18-91e9-7bbcef00525a.png)

#### Voir list order
![image](https://user-images.githubusercontent.com/76247057/209465111-3a1bd127-d1cf-4e78-b981-4c8dfa61493d.png)

#### Voir order detailes
![image](https://user-images.githubusercontent.com/76247057/209465129-2fccf46c-46c0-49e5-afb3-7317220105de.png)






