# Mano pirmoji GIT repozitorija

Ši repozitorija skirta tam, kad išmokti GIT **projektu versijavimo kontrolės komandinės eilutės sąsaja- GIT CLI.** Tam jums reikės parsisiųsti ir įsirašyti https://git-scm.com/downloads 

## Repozitorijos parsiuntimas

1. Atsidarykite GIT CLI (git bash).
2. Naudodami komanda <cd> pakeiskite save darbinę kategoriją į tą kurioje norite parsiųsti repozitoriją.
3. Parsiųskite repozitoriją git clone <https://github.com/zdvareckas/test>.
4. Pakeiskite darbinę kategoriją į parsiųstos repozitorijos kategoriją.
    cd <repozitorijos pavadinimas>
Parsisiuntę ir įsirašė GIT CLI, parsisiųskite repozitoriją, esamame kataloge.
    
## Pagrindinės komandos

- **git add** -> failų paruošimas patvirtinimui
  - **git add <failo-pavadinimas>** -> prideda failą nurodytu pavadinimu.
  - **git add .** -> prideda visus pakitusius failus.
    
- **git diff** -> skirtumas tarp dviejų failų ar dvieju to paties failo versijų
  - **git diff <failo-pavadinimas>** -> failo nurodytu pavadinimu pakitimai nuo paskutinio commit'o.
    
- **git status** -> parodo pakitusiu failų būseną

-**git branch** -> komanda kuri naudojama operacijoms su šakomis.
  -**git branch -a** -> parodo visas pariųstas šakas ir šiuo metu aktyvią šaką.
    
-**git commit** -> komanda skirta užtvirtinti projekto pakitimus.
  - **git commit -m "Žinutė apibūdinanti pakitimą"**

-**git push** -> komanda skirta paviešinti commit'us į atitinkamą globalią šaką.

