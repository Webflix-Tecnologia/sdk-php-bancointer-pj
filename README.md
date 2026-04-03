## SDK PHP Banco InterPJ

## Instalação
```console
composer install webflixtec/bancointerpj
```

## Como usar
```PHP
user \Inter\Sdk;

$interSdk = new InterSdk(
    "PRODUCTION",  //Ambiente para a requisição: PRODUCTION / SANDBOX
    "2179676f-3069-44de-96c3-07739bcded35",  //Client Id de sua integração
    "29f8fe86-efab-4b31-a5f6-6d22ebcb2014",  //Client Secret de sua integração
    "src/main/sdk/inter/certificates/production.pfx",  //path ao arquivo PFX  
    "intersdk" //senha do arquivo PFX
);
```