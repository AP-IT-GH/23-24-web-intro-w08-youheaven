# 💻 LES: W7 - API's en ThunderClient - Oefening 03

## 🛠️ Opdrachten

### ThunderClient opstarten

 - [ ] Klik op het ThunderClient icoontje om ThunderClient te openen.
   - Als je het icoontje niet vindt, controleer dan of je ThunderClient (correct) geinstalleerd hebt.

### GET request uitvoeren

 - [ ] Doe een GET request naar https://wouterpeetermans.com/iot-programming/
   - je zal een foutmelding krijgen dat je niet ingelogd bent (`unauthorized`)
 - [ ] Ga naar het tabblad "Auto" en kies voor "Basic".  
       username: `student`  
       password: `iot-programming`
 - [ ] Doe de GET request opnieuw. Nu krijg je HTML code terug als response.

### GET request met JSON response

 - [ ] Voeg aan de URL volgende string toe: `api/users/` en dan een nummer van een student  
   bv. `https://wouterpeetermans.com/iot-programming/api/users/2`
 - [ ] Schrijf de response op die je ontvangt. Let daarbij specifiek op de waarde van "state".

*schrijf hier je response op*

### POST request

 - [ ] Doe een POST request naar een student, zoals in de oefening hiervoor (maar ditmaal is het soort request dus POST).
   - Denk ook aan de login-gegevens onder het tabblad "Auth"
 - [ ] Voeg in het tabblad "body" -> "JSON" de volgende gegevens toe:  
  **als in je vorige response de "state" al op "true" stond, vul je hier "false" is ipv "true"**.

```json
{
  "state": true
}
```
 - [ ] verzend de request
 - [ ] Voer dezelfde URL uit als een POST request. Schrijf de response op die je ontvangt. Let daarbij specifiek op de waarde van "state". De "state" zou op de nieuwe waarde moeten staan.