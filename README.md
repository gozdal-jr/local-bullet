# Local bullet
System do wyświetlania lokalnego rankingu konkursów typu Náboj, zvibecodowany na potrzeby szkolnego konkursu. Nazwa pochodzi od oficjalnego nábojowego systemu [bullet](https://github.com/naboj-org/bullet), ale kod ma z nim mało wspólnego.
## Wymagania:
- [Python](https://www.python.org/downloads/) `3.10` bądź nowszy. Rekomendowany `3.12` bądź wyżej
- Przeglądarka internetowa
- git (do instalacji opcją 1, opcjonalne)
## Instalacja:
### Opcja 1:
W katalogu w którym chcesz trzymać system odpal `git clone https://github.com/sgozdal/local-bullet`. Powstanie katalog `local-bullet`.
### Opcja 2:
Skopiuj plik `local_bullet.py` z githuba do `cokolwiek.py` na swoim komputerze, całość jest używalna jako jeden plik. 
## Odpalanie
W `local-bullet` odpal plik `local_bullet.py` (najłatwiej: `python3 local_bullet.py`). Spowoduje to otworzenie się adresu `http://127.0.0.1:8000/admin` w nowej karcie przeglądarki. Pod tym adresem będzie chodził cały system. Dopóki nie postawisz w lokalnej sieci, tylko komputer na którym program zostanie odpalony będzie miał dostęp do systemu. Możesz mieć kilka kart włączonych jednoczeście, w różnych oknach różnych przeglądarek. Np.: Jedna karta to punktacja, druga to ranking na pełnym ekranie wyświetlany na jakimś ekranie dla publiki.
Jeśli port 8000 jest zajęty, system sam znajdzie wolny port na którym postawi system.

## Maintenance status — 2026-09-05

This project is retained on GitHub as a source archive (public repository). It is no longer used or installed on the owner's Mac; local checkouts, development builds and project-specific runtime files are being removed after the current source is verified on GitHub. This is a storage/maintenance decision, not a new tested application release.

To resume development, clone `gozdal-jr/local-bullet` into a temporary workspace. Build/install only when explicitly requested, push all intended source changes before removing the checkout, and keep generated binaries, credentials and user data out of Git. Repository visibility must remain public.
