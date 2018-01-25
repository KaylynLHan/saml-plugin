Changelog
-------------------
* 1.0.5 (Jan 25, 2018)
  * [JENKINS-45857](https://issues.jenkins-ci.org/browse/JENKINS-45857) Support to set the Binding type (Redirection/Post)
  * [JENKINS-47850](https://issues.jenkins-ci.org/browse/JENKINS-47850) log SAMLResponse on encoding errors
  * [JENKINS-41907](https://issues.jenkins-ci.org/browse/JENKINS-41907) Evaluate to obtain IdP Metadata from URL
  * [JENKINS-48031](https://issues.jenkins-ci.org/browse/JENKINS-48031) SAML plugin does not accept xml tag in Idp metadata (azure)
  * [JENKINS-48030](https://issues.jenkins-ci.org/browse/JENKINS-48030) SAML Azure AD exception
  * [JENKINS-47880](https://issues.jenkins-ci.org/browse/JENKINS-47880) Navigating to /securityRealm/finishLogin manually shows an odd error
  * [JENKINS-46063](https://issues.jenkins-ci.org/browse/JENKINS-46063) do not allow blank passwords
  * [JENKINS-44992](https://issues.jenkins-ci.org/browse/JENKINS-44992) SamlException after metadata update
* 1.0.4 (Sep 19, 2017)
  * [JENKINS-46949](https://issues.jenkins-ci.org/browse/JENKINS-46949) Downgrade bouncycastle-api to 2.16.1
* 1.0.3 (Aug 8, 2017)
  * [JENKINS-46007](https://issues.jenkins-ci.org/browse/JENKINS-46007) Use Secret to store keystore & storepass for SamlEncryptionData
  * [JENKINS-46039](https://issues.jenkins-ci.org/browse/JENKINS-46039) saml-idp.metadata.xml file not found (regresion)
* 1.0.2 (Aug 4, 2017)
  * Requires Java 8
  * Requires Jenkins 2.60.1
  * [JENKINS-45975](https://issues.jenkins-ci.org/browse/JENKINS-45975) Unit test (also an ATH)
  * [JENKINS-45954](https://issues.jenkins-ci.org/browse/JENKINS-45954) improvements over email attribute support
  * [JENKINS-40144](https://issues.jenkins-ci.org/browse/JENKINS-40144) Validate configuration form fields
  * [JENKINS-39602](https://issues.jenkins-ci.org/browse/JENKINS-39602) upgrade pac4j to 1.9.9
  * [JENKINS-43939](https://issues.jenkins-ci.org/browse/JENKINS-43939) Complete the implementation of SecurityRealm
* 0.14 (May 30, 2017)
  * [JENKINS-43743](https://issues.jenkins-ci.org/browse/JENKINS-43743) Enable to redirect to a custom logout URL
  * [JENKINS-37311](https://issues.jenkins-ci.org/browse/JENKINS-37311) make the logout button works
  * [JENKINS-38971](https://issues.jenkins-ci.org/browse/JENKINS-38971) Add support SAML ForceAuthn, AuthnContextClassRef, custom EntityId, and session timeout
  * [JENKINS-43736](https://issues.jenkins-ci.org/browse/JENKINS-43736) Enable to set up the user email address using SAML attribute
  * [JENKINS-38034](https://issues.jenkins-ci.org/browse/JENKINS-38034) SAML Plugin does not load groups when access with API Token
* 0.13 (Jan 25, 2017)
  * [JENKINS-39601](https://issues.jenkins-ci.org/browse/JENKINS-39601) Improve log, now you could set a logger to org.jenkinsci.plugins.saml you can see a verbose trace of the login process
  * Incorrect implementation of `loadUserByUsename`, Users are added on demand JENKINS-38228