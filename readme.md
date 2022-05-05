# PVA2 - Programování a vývoj aplikací
## Cvičení 16: Regulární výrazy

### 1
Náš systém vyžaduje od uživatele zadání uživatelského jména. Uživatelské jméno smí obsahovat pouze malá písmena a smí být maximálně 8 znaků dlouhé. Požádej uživatele o zadání uživatelského jména a pomocí regulárního výrazu vyhodnoť, zda je zadané správné.

### 2
Pro školní systém definujte ověření na školní emailové adresy.
* Na prvním místě může být jedno písmeno D, B nebo C
* Druhé až páté místo jsou číslice
* Za zavináče je uveden výraz oaopava.cz

Například: D40123@oaopava.cz	


### 3
Vytvořte program pro kontrolu správnosti SPZ vozidla.

* Na prvním místě je číslo.
* Na druhém místě písmeno, které označuje kraj.
* Na třetím místě je číslo nebo písmeno.
* Na čtvrtém místě je mezera a následuje čtveřice čísel.

Vzorek pro otestování:
Správný formát: 4P6 4482, 6A2 6635, 2AD 3424, 4C3 5025
Špatný formát: 3A 1122, A1 34567, 934 8842

B) Rozšiřte kontrolu SPZ na povolení pouze znaku kraje: A, B, C, E, H, J, K, L, M, P, S, T, U, Z.

### 4
Definujte regulární výraz pro kontrolu emailové adresy.

* Každá emailová adresa může mít před zavináčem znaky americké abecedy, číslice, tečky, podtržítko
* Doména a TLD musí obsahovat alespoň dvě písmena.
