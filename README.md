1.  Python version 3.13.7
    Installera beroenden från requirement.txt
    Kör run all i jupyter filen

2.  Krav kort till Sara, Product manager
    Prioriteringar var att sortering skall vara meningsfull (hög risk hamnar överst)
    Att workflow blir praktiskt. "Vi tar top N varje dag"

3. Vår strategi
    Vår strategi var att fokusera sig på top 5% för högrisk konton
    Detta gav oss en större träffsäkerhet att hitta bedrägerikonton i just den specifika biten av datan
    Sedan var vi mer tillåtande för falska positiva då ett flaggat konto skulle skickas vidare för manuell granskning
    därifrån bli antingen tagen för ett bedrägeri konto eller "frikänt"



4.  Tobias Uppenberg       - Dataförståelse & EDA (kort men relevant)
    Vera Stopp             - Train/test + preprocessing (korrekt workflow)
    Isac Reger             - Modellering och jämförelse
    Alexander Ahl          - Välj och optimera EN modell (hyperparameter-tuning)
    Sayed Jawid Mortazawi  - Threshold / prioritering (kopplat till kravkortet)