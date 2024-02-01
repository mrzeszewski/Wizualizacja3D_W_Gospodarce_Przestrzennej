# Wizualizacja3D_W_Gospodarce_Przestrzennej

Repozytorium materiałów ćwiczeniowych i zasobów kursu Wizualizacja 3D w Gospodarce Przestrzennej (WGESiGP UAM)

## Dodawanie modelu 3D  z georeferencjami w formacie Shapefile Multipatch (np. z SIP Poznań) do ArcGIS Online

    1. W ArcGIS Pro utworzyć nową scenę globalną (Global Scene).
    2. Zalogować się do ArcGIS Online w ArcGIS Pro (prawy górny róg).
    3. W okienku Catalog znaleźć model i przeciągnąć do okna warstwa
    4. W ustawieniach warstwy (Properties/Elevation) dopasować wysokość budynków jeśli jest taka potrzeba (np. przez offset lub wybranie Features are on the ground) 
    5. Jeśli była zmieniana wysokość należy warstwę wyeksportować ponownie używając narzędzia (z okienka Geoprocessing (można je włączyć w zakładce View) Layer 3D to Feature Class
    6. Nowa warstwa pojawi się na liście warstw. 
    7. Możemy ją wyeksportować wybierając z menu kontekstowego opcję Sharing i następnie Share as Web Layer (jeśli jest nieaktywna prawdopodobnie nie jesteśmy zalogowani do ArcGIS Online)

## Dodawanie modelu 3D bez georeferencji do ArcGIS Online

    1. W ArcGIS Pro utworzyć nową scenę globalną (Global Scene).
    2. Zalogować się do ArcGIS Online w ArcGIS Pro (prawy górny róg).
    3. Najlepiej przybliżyć teren do miejsca, w którym chcemy postawić obiekt.
    4. Trzeba utworzyć nową pustą warstwę w bazie danych. W okienku Catalog, w zakładce Project znajdujemy folder Databases. Jest tam jedna baza danych – klikamy prawym klawiszem i New/Feature Class. Nadajemy nazwę nowej warstwie i wybieramy typ jako Multipatch
    5. Warstwa zostanie dodana do listy warstw (jeśli nie – dodajemy ją ręcznie).
    6. Wybieramy warstwę, zakładkę Edit i narzędzie Create.
    7. W okienku Create wybieramy drugą ikonę (Model File). Znakiem plusa dodajemy nasz model ze ścieżki dostępu (Uwaga- jeśli model dodaliśmy już po otwarciu projektu należy widok w okienku wyboru odświeżyć)
    8. Model zostanie wczytany i od razu można go umiejscowić na mapie (jest przyczepiony do kursora). UWAGA – należy kliknąć raz – wiele kliknięć to wiele modeli. 
    9. Po umiejscowieniu zamykamy okienko Create.
    10. Należy zapisać warstwę Edit/Save
    11. Możemy warstwę wyeksportować wybierając z menu kontekstowego opcję Sharing i następnie Share as Web Layer (jeśli jest nieaktywna prawdopodobnie nie jesteśmy zalogowani do ArcGIS Online)
    12. Jeśli była zmieniana wysokość w zakładce Elevation należy warstwę wyeksportować ponownie używając narzędzia (z okienka Geoprocessing (można je włączyć w zakładce View) Layer 3D to Feature Class
