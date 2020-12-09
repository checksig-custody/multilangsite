Struttura cartelle

/_data/

/_data/locales/

/_data/locales/en.yml
/_data/locales/it.yml

Associazione di menu di contenuti per lingua

/_data/bitcoins.yml
/_data/custody.yml
/_data/images.yml
/_data/moduli.yml
/_data/partner.yml
/_data/referral.yml
/_data/sections.yml
/_data/team.yml
/_data/vision.yml

Collections di contenuti che non hanno una pagina di approfondimento

/_data/settings.yml

File contenente le associazioni per lingua delle pagine per la generazione delle sitemap IT e EN e per la sitemap hreflang


/_includes/

Include di codice html al'interno dei template presenti nella cartella /_layouts/
Non è classificato per lingua ma per sezione di inserimento. 
La lingua è definita dalla variabile "locale" presente nei file .md della cartella /content/en/ o /content/it/


/_includes/company/

/_includes/custody/

/_includes/custody/custody.html
/_includes/custody/custody-module.html
/_includes/custody/nav_custody.html


/_includes/faq/
/_includes/home/
/_includes/institutions/
/_includes/solutions/
/_includes/footer-checksig.html
/_includes/head-checksig.html
/_includes/header-checksig.html
/_includes/language-selector.html
/_includes/menu.html
/_includes/moduli.html
/_includes/script-checksig.html
/_includes/solutions.html
/_includes/why-bitcoins.html

/_layouts/

Template delle pagine: anche questi non sono classificati per lingua. 
Le sottopagine hanno un template con il suffisso _child

/_layouts/bitcoin.html
/_layouts/company.html
/_layouts/contact.html
/_layouts/custody.html
/_layouts/custody_child.html
/_layouts/default.html
/_layouts/faq_child.html
/_layouts/home.html
/_layouts/institution_child.html
/_layouts/institutions.html
/_layouts/page.html
/_layouts/post.html
/_layouts/solutions.html
/_layouts/support.html


/assets/

Cartella con le immagini, file css e file js

/content/

Cartella per i contenuti del sito con 2 sottocartelle di lingua.
I file .md delle pagine principali sono nella root, ad esempio /content/en. 
La lista di sottopagine sono raggruppate i sottocartelle con il nome della pagina padre /content/en/custody

/content/en/

/content/en/_posts/
/content/en/company/
/content/en/custody/

/content/en/custody/transparency.md
/content/en/custody/technology.md
/content/en/custody/security.md
/content/en/custody/patent.md
/content/en/custody/insurance-coverage.md
/content/en/custody/certifications.md

/content/en/faq/
/content/en/institutions/
/content/en/solutions/
/content/en/company.md
/content/en/contact.md
/content/en/custody.md
/content/en/institutions.md
/content/en/support.md
/content/en/why-bitcoin.md


/content/it/

/content/it/_posts/
/content/it/company/
/content/it/custody/

/content/it/custody/transparency.md
/content/it/custody/technology.md
/content/it/custody/security.md
/content/it/custody/patent.md
/content/it/custody/insurance-coverage.md
/content/it/custody/certifications.md


/content/it/faq/
/content/it/institutions/
/content/it/solutions/
/content/it/company.md
/content/it/contact.md
/content/it/custody.md
/content/it/institutions.md
/content/it/support.md
/content/it/why-bitcoin.md

Nella root sono presenti le 2 homepage IT e EN

/index.html
/index_it.html