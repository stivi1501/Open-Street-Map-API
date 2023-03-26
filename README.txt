1.Wstęp
Projekt jest praktycznym przykładem prezentującym rozwiązania pomocne w wykorzystaniu podkładów mapowych w przyszłych projektach.

2.Użyte technologie:
- JavaScript (struktura dokumentu według DOM, fetch do pobierania plików, przerwania wywoływane zdarzeniami),
- kaskadowe arkusze styli CSS,
- podkłady mapowe Open Street Map.

3.W celu prezentacji działania należy pobrać projekt i rozpakować go w katalogu htdocs serwera typu Apache.
W przypadku braku użycia serwera WWW część z funkcji nie będzie działać.

4. Główne funkcjonalności
Po wpisaniu odpowiedniego adresu (u mnie http://localhost/OSM.html) okno przeglądarki wypełni mapa z podkładami Open Street Map. Po kliknięciu w dowolny punkt mapy pokaże się formatka ze współrzędnymi klikniętego punktu. W przypadku przesunięcia mapy (przytrzymanie lewego klawisza i ruch myszką pokaże się formatka zawierająca parametry krawędzi mapy, zoom mapy, parametry kliknięcia oraz rozmiar diva, na którym prezentuje się mapa (rys.1).
<img src="OSM_EDGE.PNG" alt="Flowers in Chania">
Po najechaniu na szary obszar po prawej stronie okna przeglądarki wyskoczy nam menu, w którym są odsyłacze do zaznaczania markerów na mapie (rys.2).
<img src="OSM_DRAW_MARKERS.PNG" alt="Flowers in Chania">


