# Mano pirmoji GIT repozitorija

Ši repozitorija skirta tam, kad išmokti GIT projektu versijavimo kontrolės komandinės eilutės sąsaja- GIT CLI. Tam jums reikės parsisiųsti ir įsirašyti https://git-scm.com/downloads 

## Repozitorijos parsiuntimas
Parsisiuntę ir įsirašė GIT CLI 
    git clone <https://github.com/zdvareckas/test>
## Pagrindinės komandos
    git add -> failų paruošimas patvirtinimui
        git add <failo-pavadinimas> -> prideda failą nurodytu pavadinimu.
        git add . -> prideda visus pakitusius failus.
    
    git diff -> skirtumas tarp dviejų failų ar dvieju to paties failo versijų
        git diff <failo-pavadinimas> -> failo nurodytu pavadinimu pakitimai nuo paskutinio commit'o.
    
    git status -> parodo pakitusiu failų būseną

    git branch -> komanda kuri naudojama operacijoms su šakomis.
        git branch -a -> parodo visas pariųstas šakas ir šiuo metu aktyvią šaką.
    
    git commit -> komanda skirta užtvirtinti projekto pakitimus.
        git commit -m "Žinutė apibūdinanti pakitimą"

    git push -> komanda skirta paviešinti commit'us į atitinkamą globalią šaką.

