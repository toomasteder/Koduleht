# Koduleht

## Eeldused
SSH võti lisatud Githubi kontole.  SSH võtmete hulka

## Alla laadimiseks esimest korda arvutis
Kirjutan terminali soovitud kaustas olles:
git clone git@github.com:toomasteder/koduleht.git

## Muutuste alla laadimine
git pull

## Muutuste lisamine
git add . (punkt lisab kõik failid. Kui soovin konkreetset faili, lisan git add failinimi)

## Muutuse kommentaari lisamine
git commit-m"Muutuse kirjeldus"

## Muutuse serverisse lisamine
git push


## Üleslaadimiseks
githubis uus repository
navigeeri bashis kausta kust laed
  egit commit -m "first commit"
  cho "# koduleht" >> README.md
  git branch -M main
  git remote add origin git@github.com:toomasteder/koduleht.git
  git push -u origin main
