# Clase Asset

Se usa para representar la estructura de datos de un activo.

Namespace: [Neo.SmartContract.Framework.Services.Neo](../neo.md)

Assembly: Neo.SmartContract.Framework

## Sintaxis

```c#
public class Asset
```

## Atributos

| | Nombre | Descripción |
| ---------------------------------------- | ------------------------------- | ------------------------------------- |
[Admin](Asset/Admin.md) | Obtiene el administrador (dirección contrato) del activo. |
|[Amount](Asset/Amount.md) | Obtiene la cantidad total del activo. |
[AssetId](Asset/AssetId.md) | Obtiene el Id del activo. |
[AssetType](Asset/AssetType.md) | Obtiene la categoria del activo. |
[Available](Asset/Available.md) | Obtiene la cantidad del activo que ha sido emitido.|
[Issuer](Asset/Issuer.md) | Obtiene el emisor del activo. (dirección del contrato) |
[Owner](Asset/Owner.md) | Obtiene el propietario (clave pública) del activo | 
[Precision](Asset/Precision.md) | Obtiene la precición del activo (el número mínimo de divisiones)| El número de dígitos después del punto decimal.

## Método

|  | Nombre | Descripción |
| ---------------------------------------- | ----------------------------- | ----------- |
|![](https://i-msdn.sec.s-msft.com/dynimg/IC91302.jpeg) | [Renew (byte)](Asset/Renew.md) | `new` Renovar un asset. |

## Método del constructor

Construye un objecto Asset con el metodo [Blockchain.GetAsset (byte[])](Blockchain/GetAsset.md)

El metodo [Blockchain.CreateAsset](Blockchain/CreateAsset.md) crea un nuevo asset en la blockchain y devuelve un objeto
del tipo Asset (blockchain, string, long, byte, byte[], byte[], byte[])
