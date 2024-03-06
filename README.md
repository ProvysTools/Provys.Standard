# Provys.Standard

Melo by obsahovat spolecne veci psane v NetStandard (pouzitelne jak v NET tak v NET FW).
Nemelo by mit zadnou zavislost na jine nasi knihovne vyjma Provys.Standard.Base a Provys.Standard.SystemEx.

#### ProvysServerEncryption
 
``` csharp
// example
var result = ProvysServerEncryption.Encrypt("textToEncrypt");
var result = ProvysServerEncryption.Decrypt("IIS$U70nF9A4uQPr2mfdDPTy6C1DkiVpVA==");
```

