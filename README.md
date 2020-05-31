Start the Service Provider:

```bash
./gradlew demo-saml-sp:bootRun
```

Start the Identity Provider:

```bash
./gradlew demo-saml-idp:bootRun
```          

### IDP-initiated Flow

Open http://localhost:9092/demo-idp in your browser.

Input user1/1q2w3e4r into Username and Password inputs.

Click on "Spring Security SAML SP (local)". You should be able to see the welcome page with 
the SAML assertion xml.
