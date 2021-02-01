# Optimitzacio_de_programari_UF2_1
## Introducció
* Les proves es centren principalment en que el programari faci el que ha de fer i res més.
* A vegades aquestes proves es fan amb ajuda de marcs de treball (Frameworks)
* Un framework o marc de treball esta compost per un conjunt de eines, biblioteques i un conjunt de bones practiues per el desenvolupament. La finalitat d'aquest és unificar el desenvolupament.
## Proves
* Forma de les proves.
  *  Poves dinamiques: Requereixen l'execucio de l'app, permet fer una valoracio del comportament de l'app. 
  * Proves estàtiques: S'examina el codi font de l'applicacio, sense executar-la.
* Estrategies de prova
  * Caixa negra: Proves de funcionalitat on s'estudia el sistema desde fora. Es treballa sobre la interficie d'usuari sense tenir en compte el funcionament intern. Consisteix en proporcioanr entrades i veure les sortides.
  * Caixa blanca: S'examina el codi font i la seva execucio. Son proves estructurals on s'examina el el fluxe tant entre unitats com dins de cada unitat. Tambe es fan entre sistemes. Les tecniques principals son la cobertura del codi (%del codi que s'executa, mes aprop del 100% millot) i la prova de bucles.
* Tipos de proves
  * Funcionals: Evaluen si el programa fa el que ha de fer i compleix els requisits incialment marcats.
  * Exemples roves funcionals : Proves unitaries, de regresio, de integració, smoke test, del sistema, proves alfa i beta, i proves de validacio per part del client.
  * No funcionals: Evaluen altres aspectes com el rendiment, la seguretat...
  * Exemples Proves no funcionals : Proves de usabilitat, rendiment, stress, seguretat, compatibilitat, portabilitat etc.
* Mecanismes de prova
  * Manual: Mitjançant proves realitzades per personal de l'empresa o extern. 11 factors de qualitat, repartits en 3 ambits, l'opracio del producte, la revisio del producte, la transicio del producte.
  * Automatica: Mitjançant software que executa el codi de forma automatizada i compara els resultats obtinguts i esperats.
* Suport del depurador.
  * Punts de ruptura, execusio pas a pas i analisis de variables.
* Automatitzacio de proves:
  * Frameworks de proves (xUnit)
  * Asercions 
* Framewokrs per a proves

  * Java: JUnit, TestNG
  * C++: CppUnit, Google Test
  * PHP: PHPUnit
  * Javascript: Mocha
* Case de prova: Un de prova es un set d'entrades per les quals es coneix la sortida, es fa servir per verificar el correcte funcionament del codi sobretot per les funcions.
* TDD (Test Diven Developement): S'escriuen abans les proves.

## Integració
* Integracio Bing Bang
* Integració Descendent
* Integració Ascendent
* Integració continua(Cl)/CD (Continus Delivery)
  * Jenkins
  * Bamboo
  * Travis CL

## Qualitat.
* Control de qualitat
  * Es realitzen proves per valorar la qualitat del resultat.
* Qualitat del proces/producte
  * QA (Quality Assurance) Es un conjunt d'activitats que es realitzen per tal de poder garantir la qualitat del processos que es fan servir per desenvolupar el producte.
  * QC (qualitty control) Es un conjunt d'activitats centrades en la identificació dels defectes dels productes.
* Factors de qualitat
  * El model de qualitat McCall defineix 11 factors de qualitat, repartits en 3 ambits, l'opració del producte (Correcció, Fiabilitat, Seguretat, Eficiencia, Facilitat d'us ), 
 la revisio del producte (Mantenibilitat, Flexibilitat, Facilitat de prova), la transicio del producte (Portabilitat, Reusabilitat, Interoperabilitat).
