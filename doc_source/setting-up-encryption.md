# Step 6\. Set Up Encryption \(optional\)<a name="setting-up-encryption"></a>

You can protect your content from unauthorized use through encryption\. If your source is encrypted, AWS Elemental MediaConnect can decrypt it\. In addition, the service can encrypt outputs\. You store your encryption keys in AWS Secrets Manager, and then give AWS Elemental MediaConnect permission to obtain the encryption keys from your Secrets Manager account\. For more information, see [Encryption in Transit](encryption-in-transit.md)\.