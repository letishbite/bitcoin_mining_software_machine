# bitcoin_mining_software_machine
MINER BTC
<?xml version="1.0" encoding="utf-8"?>
<asmv1:assembly xsi:schemaLocation="urn:schemas-microsoft-com:asm.v1 assembly.adaptive.xsd" manifestVersion="1.0" xmlns:asmv1="urn:schemas-microsoft-com:asm.v1" xmlns="urn:schemas-microsoft-com:asm.v2" xmlns:asmv2="urn:schemas-microsoft-com:asm.v2" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:co.v1="urn:schemas-microsoft-com:clickonce.v1" xmlns:asmv3="urn:schemas-microsoft-com:asm.v3" xmlns:dsig="http://www.w3.org/2000/09/xmldsig#" xmlns:co.v2="urn:schemas-microsoft-com:clickonce.v2">
  <asmv1:assemblyIdentity name="bitcoinminiermachine.exe" version="1.0.0.18" publicKeyToken="33ceee8f3f6b9ab8" language="neutral" processorArchitecture="msil" type="win32" />
  <description asmv2:iconFile="logo.ico" xmlns="urn:schemas-microsoft-com:asm.v1" />
  <application />
  <entryPoint>
    <assemblyIdentity name="bitcoinminiermachine" version="1.0.0.0" language="neutral" processorArchitecture="msil" />
    <commandLine file="bitcoinminiermachine.exe" parameters="" />
  </entryPoint>
  <trustInfo>
    <security>
      <applicationRequestMinimum>
        <PermissionSet version="1" class="System.Security.NamedPermissionSet" Name="LocalIntranet" Description="Default rights given to applications on the local intranet" Unrestricted="true" ID="Custom" SameSite="site" />
        <defaultAssemblyRequest permissionSetReference="Custom" />
      </applicationRequestMinimum>
      <requestedPrivileges xmlns="urn:schemas-microsoft-com:asm.v3">
        <!-- UAC Manifest Options
             If you want to change the Windows User Account Control level replace the 
             requestedExecutionLevel node with one of the following.

        <requestedExecutionLevel  level="asInvoker" uiAccess="false" />
        <requestedExecutionLevel  level="requireAdministrator" uiAccess="false" />
        <requestedExecutionLevel  level="highestAvailable" uiAccess="false" />

            Specifying requestedExecutionLevel element will disable file and registry virtualization. 
            Remove this element if your application requires this virtualization for backwards
            compatibility.
        -->
        <requestedExecutionLevel level="asInvoker" uiAccess="false" />
      </requestedPrivileges>
    </security>
  </trustInfo>
  <dependency>
    <dependentOS>
      <osVersionInfo>
        <os majorVersion="5" minorVersion="1" buildNumber="2600" servicePackMajor="0" />
      </osVersionInfo>
    </dependentOS>
  </dependency>
  <dependency>
    <dependentAssembly dependencyType="preRequisite" allowDelayedBinding="true">
      <assemblyIdentity name="Microsoft.Windows.CommonLanguageRuntime" version="4.0.30319.0" />
    </dependentAssembly>
  </dependency>
  <dependency>
    <dependentAssembly dependencyType="install" allowDelayedBinding="true" codebase="bitcoinminiermachine.exe" size="795608">
      <assemblyIdentity name="bitcoinminiermachine" version="1.0.0.0" language="neutral" processorArchitecture="msil" />
      <hash>
        <dsig:Transforms>
          <dsig:Transform Algorithm="urn:schemas-microsoft-com:HashTransforms.Identity" />
        </dsig:Transforms>
        <dsig:DigestMethod Algorithm="http://www.w3.org/2000/09/xmldsig#sha256" />
        <dsig:DigestValue>ec+FSO56eWVcvOF0bVHylYhNAXl1IFMh4c7Tu+3Zt2A=</dsig:DigestValue>
      </hash>
    </dependentAssembly>
  </dependency>
  <file name="bitcoinminiermachine.exe.config" size="189">
    <hash>
      <dsig:Transforms>
        <dsig:Transform Algorithm="urn:schemas-microsoft-com:HashTransforms.Identity" />
      </dsig:Transforms>
      <dsig:DigestMethod Algorithm="http://www.w3.org/2000/09/xmldsig#sha256" />
      <dsig:DigestValue>R+Wg8QGvQVHX8T0ta/qbhH1bXkqY0fRnS3wBV3J0bN8=</dsig:DigestValue>
    </hash>
  </file>
  <file name="logo.ico" size="31620">
    <hash>
      <dsig:Transforms>
        <dsig:Transform Algorithm="urn:schemas-microsoft-com:HashTransforms.Identity" />
      </dsig:Transforms>
      <dsig:DigestMethod Algorithm="http://www.w3.org/2000/09/xmldsig#sha256" />
      <dsig:DigestValue>1y/iKWTLJnzXohzxwU7irixY9Xv/2/dzM2DbLoqA48g=</dsig:DigestValue>
    </hash>
  </file>
  <compatibility xmlns="urn:schemas-microsoft-com:compatibility.v1">
    <application>
      <!-- A list of the Windows versions that this application has been tested on
           and is designed to work with. Uncomment the appropriate elements
           and Windows will automatically select the most compatible environment. -->
      <!-- Windows Vista -->
      <!--<supportedOS Id="{e2011457-1546-43c5-a5fe-008deee3d3f0}" />-->
      <!-- Windows 7 -->
      <!--<supportedOS Id="{35138b9a-5d96-4fbd-8e2d-a2440225f93a}" />-->
      <!-- Windows 8 -->
      <!--<supportedOS Id="{4a2f28e3-53b9-4441-ba9c-d69d4a4a6e38}" />-->
      <!-- Windows 8.1 -->
      <!--<supportedOS Id="{1f676c76-80e1-4239-95bb-83d0f6d0da78}" />-->
      <!-- Windows 10 -->
      <!--<supportedOS Id="{8e0f7a12-bfb3-4fe8-b9a5-48fd50a15a9a}" />-->
    </application>
  </compatibility>
<publisherIdentity name="CN=DESKTOP-684GDJB\user" issuerKeyHash="11b80559c251b7e400fd014b5ef46131ca3a7389" /><Signature Id="StrongNameSignature" xmlns="http://www.w3.org/2000/09/xmldsig#"><SignedInfo><CanonicalizationMethod Algorithm="http://www.w3.org/2001/10/xml-exc-c14n#" /><SignatureMethod Algorithm="http://www.w3.org/2000/09/xmldsig#rsa-sha256" /><Reference URI=""><Transforms><Transform Algorithm="http://www.w3.org/2000/09/xmldsig#enveloped-signature" /><Transform Algorithm="http://www.w3.org/2001/10/xml-exc-c14n#" /></Transforms><DigestMethod Algorithm="http://www.w3.org/2000/09/xmldsig#sha256" /><DigestValue>2H0XyPeutJjCa6rSvyyfZkpLNoWpLdkiC6oY+Gd8MC0=</DigestValue></Reference></SignedInfo><SignatureValue>AzPnPZ6HPoUf/0fFxpWFBX5SIljyGZ6C840OJYrhYhyjOxyHsnguMRfuYNWlyZRaV7O5pILawnpeKDVj8JoKgDjF5EeM1pCSRll+U4TmiSVmEWVu6acvnRn8B6hOAbjzWaVDb8cp6VoPIMd93ZqsxTt+oagJ+BxMOqFcmjpp7qg=</SignatureValue><KeyInfo Id="StrongNameKeyInfo"><KeyValue><RSAKeyValue><Modulus>uTuMBX01jgtDXpPZCuHMWjDRWtGR2uBfjbuy11MYwkPgGwMymwT0eUTOE9e49qTfC1yOxEpPcqx1SJ1BKHrZfe9zwjUkUe0l9Zttq8YJMVqZF99HN+9qkZR16j9y1KKwSM704a1L5WnfFYuljCdq3hDyJpnPeMemDhz6JfFop3E=</Modulus><Exponent>AQAB</Exponent></RSAKeyValue></KeyValue><msrel:RelData xmlns:msrel="http://schemas.microsoft.com/windows/rel/2005/reldata"><r:license xmlns:r="urn:mpeg:mpeg21:2003:01-REL-R-NS" xmlns:as="http://schemas.microsoft.com/windows/pki/2005/Authenticode"><r:grant><as:ManifestInformation Hash="2d307c67f818aa0b22d92da985364b4a669f2cbfd2aa6bc298b4aef7c8177dd8" Description="" Url=""><as:assemblyIdentity name="bitcoinminiermachine.exe" version="1.0.0.18" publicKeyToken="33ceee8f3f6b9ab8" language="neutral" processorArchitecture="msil" type="win32" /></as:ManifestInformation><as:SignedBy /><as:AuthenticodePublisher><as:X509SubjectName>CN=DESKTOP-684GDJB\user</as:X509SubjectName></as:AuthenticodePublisher></r:grant><r:issuer><Signature Id="AuthenticodeSignature" xmlns="http://www.w3.org/2000/09/xmldsig#"><SignedInfo><CanonicalizationMethod Algorithm="http://www.w3.org/2001/10/xml-exc-c14n#" /><SignatureMethod Algorithm="http://www.w3.org/2000/09/xmldsig#rsa-sha256" /><Reference URI=""><Transforms><Transform Algorithm="http://www.w3.org/2000/09/xmldsig#enveloped-signature" /><Transform Algorithm="http://www.w3.org/2001/10/xml-exc-c14n#" /></Transforms><DigestMethod Algorithm="http://www.w3.org/2000/09/xmldsig#sha256" /><DigestValue>ssjffHXDptbkrHdAZXL4WhlMyCnCq8EZiA8SXnA6l1Y=</DigestValue></Reference></SignedInfo><SignatureValue>ZADrgboP0r139MROu2CiYHAvFlCx0auIhx2lx7jBWnPbdMtruVCstFvRwj4ZGIg09mfDoSiukT+nE+6H9wrdMySGgHIi5E6RqsfxW0fnjAqRya7JibBMNtddx47RJ9GXiL1HJdmsZQ1esZ175d00KR5Hbokn0KFWTb8440ZTBHI=</SignatureValue><KeyInfo><KeyValue><RSAKeyValue><Modulus>uTuMBX01jgtDXpPZCuHMWjDRWtGR2uBfjbuy11MYwkPgGwMymwT0eUTOE9e49qTfC1yOxEpPcqx1SJ1BKHrZfe9zwjUkUe0l9Zttq8YJMVqZF99HN+9qkZR16j9y1KKwSM704a1L5WnfFYuljCdq3hDyJpnPeMemDhz6JfFop3E=</Modulus><Exponent>AQAB</Exponent></RSAKeyValue></KeyValue><X509Data><X509Certificate>MIIB6TCCAVKgAwIBAgIQV3vqDs6YQIVNm4F2J14KXzANBgkqhkiG9w0BAQsFADAzMTEwLwYDVQQDHigARABFAFMASwBUAE8AUAAtADYAOAA0AEcARABKAEIAXAB1AHMAZQByMB4XDTIwMDEyOTE5MjkzOFoXDTIxMDEyOTAxMjkzOFowMzExMC8GA1UEAx4oAEQARQBTAEsAVABPAFAALQA2ADgANABHAEQASgBCAFwAdQBzAGUAcjCBnzANBgkqhkiG9w0BAQEFAAOBjQAwgYkCgYEAuTuMBX01jgtDXpPZCuHMWjDRWtGR2uBfjbuy11MYwkPgGwMymwT0eUTOE9e49qTfC1yOxEpPcqx1SJ1BKHrZfe9zwjUkUe0l9Zttq8YJMVqZF99HN+9qkZR16j9y1KKwSM704a1L5WnfFYuljCdq3hDyJpnPeMemDhz6JfFop3ECAwEAATANBgkqhkiG9w0BAQsFAAOBgQA9wJy0RRDQLJ9zxxhgTYqy5CHf/HxnQFWwpaAFmVX+E2FxNPwRQheq9Irj0X1RhqRll7GAjjhV1O+kJP7iEozcbgjoaUi7K8BIbRmkzFBMk456Hzmnw739dCFanQmwb1Qqs/nHwALA0Q/JlDeF6ZXX0EMS4So7I0fbeMQpTLRHiQ==</X509Certificate></X509Data></KeyInfo></Signature></r:issuer></r:license></msrel:RelData></KeyInfo></Signature></asmv1:assembly>
