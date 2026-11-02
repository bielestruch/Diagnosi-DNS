## Què és el DNS?

- Sistema de Noms de Domini
- Relaciona noms amb adreces IP
- Facilita l'accés als serveis
- Exemple: www.google.com → adreça IP

## Com es registra un nom de domini?

- Escollir un nom
- Comprovar si està disponible
- Registrar-lo
- Configurar els servidors DNS
- Crear els registres DNS

## Arquitectura DNS

Client

   ↓

Servidor DNS recursiu

   ↓

Root Server

   ↓

Servidor TLD

   ↓

Servidor autoritatiu

## Estructura jeràrquica del DNS
A la diapositiva:
.
└── es
    └── exemple
        └── www

També pots posar:

Arrel → TLD → Domini → Subdomini/host

## Com funciona la resolució de noms?

Nom de domini
      ↓
DNS recursiu
      ↓
Root Server
      ↓
Servidor TLD
      ↓
Servidor autoritatiu
      ↓
Adreça IP

## Consultes recursives i iteratives

Consulta recursiva
El servidor busca la resposta completa.
Consulta iterativa
El servidor indica on continuar buscant.

I també:
- Root Server → indica el TLD
- Servidor autoritatiu → resposta oficial

## Zones DNS

ZONES DNS

Zona directa
Nom → IP

Zona inversa
IP → Nom

Zona primària
Informació principal

Zona secundària
Còpia de la informació

## mDNS
A la diapositiva:
mDNS
- Xarxa local
- Multicast
- Noms .local
- UDP 5353
- 224.0.0.251
Exemple:
Ordinador
    ↓
"Qui és impressora.local?"
    ↓
Xarxa local
    ↓
Impressora
    ↓
"Soc jo"

## Mapa conceptual i resum


![alt text](image.png)