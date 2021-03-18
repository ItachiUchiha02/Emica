# Emica
Repository for Emica - Learning web programming

# PODSETNIK ZA GIT #
Pre bilo kakve operacije proveriti status nad gitom
git status

Nakon provere, ukoliko je sve cisto moze se uraditi push ili pull

Ukoliko imamo kod za push (kod koji zelimo da posaljemo) radimo push sledecim koracima
    1. git add -A (komanda kojom promene i nove fajlove spremamo za commit)
    2. git commit -m "poruka_naseg_commita" (sam commit nasih fajlova, priprema za push, poruka sto kraca i jasna i na engleskom)
    3. git push (push, odnosno slanje nasih fajlova)

Ukoliko zelimo da pullujemo neki kod (prebacimo kod nas u program) radimo sledecu komandu
    1. git pull

# HAPPY CODING <3

# PROJEKAT BR. 2

Zelimo main div da ima osnovne karakteristike za postavku.
Osnovne karakteristike su:
    1. max-width: 1320px; // Ovo sluzi da se odredi najveca moguca sirina main div-a, van ove sirine nece ici bez obzira koliki je ekran
    2. width: 100%; // Ovo sluzi da uvek zauzima punu sirinu koju smo odredili, na velikim ekranima to iznosi 1320px (jer smo tako podesili, a kako se smanjuje ekran tako ce i sirina)
    3. padding: 0 20px; // Sluzi za detaljno centriranje main div-a
    4. margin: 30px auto; // Osnovno centriranje po sredini ekrana, i odvajanje od header-a i footer-a
    5. box-sizing: border-box; // Sluzi za fiksiranje granica main div-a, da padding koji smo postavili ne ide van granica nasih 1380px sirine


    * JEDAN OD NACINA RASPOREDJIVANJA DIVA
       display: flex;
       justify-content: space-between;
       width: 70%;
       margin: 0 auto;
}   *
