# Projekt-Setup-Anleitung Coderr Projekt (Coderr_frontend_v1.1.0)  
## Diese Anleitung beschreibt die Schritte zur Installation und Konfiguration des Projekts Coderr in VS-Code.

## Installation und Einrichtung
  Lade dir VS-Code herunter und starte es. Öffne das Projekt (Folder) Coderr-Frontend.
  
### - Extensions: Live Server 
  Lade unter Extensions 'Live Server' herunter. Zum Beispiel von Ritwick Dey.
  
### - Webserver starten
  Öffne die index.html Datei und drücke unten rechts unten auf 'Go Live'. 


# Config (config.js)

const GUEST_LOGINS = {
    customer : {
        username: 'andrey',
        password: 'asdasd'
    },
    business : {
        username: 'kevin',
        password: 'asdasd24'
    }
}

const API_BASE_URL = 'http://127.0.0.1:8000/api/';

const STATIC_BASE_URL = 'http://127.0.0.1:8000/';

const LOGIN_URL = 'login/';

const REGISTER_URL = 'registration/';

const PROFILE_URL = 'profile/';

const BUSINESS_PROFILES_URL = 'profiles/business/';

const CUSTOMER_PROFILES_URL = 'profiles/customer/';

const REVIEW_URL = 'reviews/';

const ORDER_URL = 'orders/';

const OFFER_URL = 'offers/';

const OFFER_DETAIL_URL = 'offerdetails/';

const BASE_INFO_URL = 'base-info/';

const OFFER_INPROGRESS_COUNT_URL = 'order-count/';

const OFFER_COMPLETED_COUNT_URL = 'completed-order-count/';

const PAGE_SIZE = 6;
