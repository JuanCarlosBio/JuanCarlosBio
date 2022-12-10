# **BIOLOGIST** :man_scientist: :lab_coat: :microscope: :petri_dish: :test_tube: :mouse2: :hiking_boot: :ant: :hibiscus: :seedling: :mushroom:

* ## **BIOINFORMATICS STUDENT** :man_technologist: :computer: :bar_chart: :chart_with_upwards_trend: :dna:

### <p align="center">You Know, I'm something of a scientist myself</p> 

* ## **CANARY ISLANDS** :desert_island:

# Input
```
#!/usr/bin/env bash

me="JuanCarlos"
grade="Biology"
master="Bioinformatics"

if [[ $me == JuanCarlos && $grade ==  Biology && $master == Bioinformatics ]]
then
        echo "Hello GitHub world, my name is Juan Carlos, I am from Canary Islands and I like programming and biology"
        echo "Graduate in Biology University of La Laguna, Tenerife 2019-2022 (ULL)"
        echo "Currently doing a Master Degree in Bioinformatics Valencian International University (VIU)"
else
        echo "Impossible, perhaps the archives are incomplete"
fi

```

# Output

---

```
Hello GitHub world, my name is Juan Carlos, I am from Canary Islands and I like programming and biology
Graduate in Biology University of La Laguna, Tenerife 2019-2022 (ULL)
Currently doing a Master Degree in Bioinformatics Valencian International University (VIU)
```

---

mkdir -p ~/miniconda3
#descargar el instalador
wget repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O
~/miniconda3/miniconda.sh
#correr el instalador
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
#eliminar el instalador
rm -rf ~/miniconda3/miniconda.sh
#ejecutar conda por defecto en el terminal
~/miniconda3/bin/conda init bash
