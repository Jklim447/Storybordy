# The script of the game goes in this file.

# Declare characters used by this game. The color argument colorizes the
# name of the character.

#main_menu_background

# The game starts here.

label start:
    $renpy.movie_cutscene( "Final_Ascent.webm")

    # Show a background. This uses a placeholder by default, but you can
    # add a file (named either "bg room.png" or "bg room.jpg") to the
    # images directory to show it.

    scene bg_maszynownia with dissolve

    # This shows a character sprite. A placeholder is used, but you can
    # replace it by adding a file named "eileen happy.png" to the images
    # directory.


    show rose at left  with dissolve

    # These display lines of dialogue.



    play music normal_sound


    rose "Czas wziąć się do pracy!"
    narrator "Biomechaniczna struktura miasta to zarówno maszyna jak i organizm.
     Setki techników takich jak Rose codziennie pracują by utrzymać ją w dobrym
      zdrowiu."
    narrator "Każdy technik jest jednocześnie inżynierem jak i lekarzem.
    Jeden błąd może zaważyć o losie całej masywnej, lecz delikatnej wewnątrz
     struktury."
    narrator "To zwykły dzień pracy dla Rose. Rutynowa inspekcja systemu
    limfatycznego złożonego z pulsujących kanałów tkanki poprzecinanych
     stalowymi rurami"
    narrator " Rose Przygląda się częściom w poszukiwania usterek.
    Znajduje drobny wyciek płynów w jednej z rur."
    narrator "Po oględzinach zaczyna rozkładać narzędzia i przygotowywać się do
     pracy"
    rose "Hmm... mam wrażenie,że czegoś zapomniałam..."
    narrator " Nagle do pomieszczenia wbiega postać o długich fioletowych
    włosach z pojemnikiem w ręku"
    show mira at right  with dissolve
    show rose_suprised at left
    rose " Mira?"
    rose"Co ty tu robisz? Coś się stało?"
    mira " Daj mi chwilkę żeby odsapnąć"
    mira" Pomyśleć,że pokonujesz taki kawał drogi dwa razy dziennie...
     Płuca zaraz wypluję"
    rose " Wiesz,dlatego dojeżdzam skuterem..."
    mira " Nawet nic nie mów... Przebiegłam ten kawał drogi bo znowu
    zapomniałaś wziąć obiad, który ci przygotowałam do pracy!"
    show rose_looking_at_mira at left
    rose " I przyszłaś tutaj tylko po to żeby  mi go przynieść? Naprawdę nie
     musiałaś"
    mira "Oczywiście ,że musiałam .Nie mogę pozwolić na to  żebyś mi tu umarła
     z głodu"
    mira "Ahh..Chciałabym zostać dłużej, ale muszę już iść. I tak jestem
     spóźniona"
    rose "Sorka, że przeze mnie musiałaś się fatygować..."
    mira "Dla ciebie wszystko!Do zobaczenia później"
    hide mira
    show rose
    narrator "Po pożeganiu Rose zasiadła do pracy. Po paru minutach jej
    czynność jest ponownie przerwana przez pojawienie się tajemniczej paczki"
    stop  music fadeout 1.0
    play music dark_sound
    hide rose_suprised
    hide rose_looking_at_mira
    hide rose
    show asset
    narrator "W środku znajduje się list z wypisanymi imionami
     oraz pistolet z nabojami usypiającymi"
    hide asset
    show rose_terryfied
    rose "Nie, to nie możliwe... to musi być pomyłka!"
    rose "Mira... moja Mira?"
    rose "Wiedziałam ,że ten dzień kiedyś nadejdzie. To mój obowiązek, miasto
    daje nam życie a dinozaur musi żyć bez względu na cenę..."
    rose "Ale Mira? Nie dam rady, nie mogę tego zrobić"
    narrator "Po długim czasie Rose uspokoiła myśli"
    show rose_sad
    rose "Jako mechanik muszę wykonać swój obowiązek..."
    stop music



    menu:
        "Znajdź Luisa":
         call GotoLuis
        "Znajdź Emily":
         call GotoEmily
        "Poszukaj wskazówek kim jest Rutger":
         call GotoRutger






    return
    label GotoLuis:
    play music city_sound
    rose "Nie mam czasu się zastanawiać , muszę znaleźć pierwszą osobę z
    listy. Luis... wielokrotnie oglądałam jego występy razem z Mirą.
    Jestem pewna,że znajdę go w mieście niedaleko cyrku."
    hide rose_sad
    scene bg_miasto
    show rose at right with dissolve
    rose "Wygląda na to ,że przyszłam w idealnym momencie! Luis akurat kończy
    swój uliczny występ. Muszę go jakoś zaprowadzić do miejsca wyznaczonego przez
    przełożonych, tylko jak go przekonać..."
    rose "Jak tak teraz o tym myślę czy ja kiedykolwiek z nim
    rozmawiałam? Byłam na wielu jego występach, ale przecież jestem dla
    niego zupełnie obcą osobą"
    rose "Nie mogę przecież tak po prostu do niego podejść. Jakby do
    mnie przyszła jakaś obca osoba i poprosiła żebym z nią poszła w
    jakieś  podejrzane miejsce to bym od razu uciekła. To się nie
    może udać..."
    narrator "W momencie, kiedy Rose mocno rozmyśla, co zrobić, Luis
    kończy występ i schodzi ze sceny"
    rose "Huh? Gdzie on się podział?"
    rose "Jest ! Nie mogę pozwolić mu uciec!"
    rose "Luis!"
    show luis at left with dissolve
    narrator ""






    return
    label GotoEmily:
    play music city_sound
    rose "Nie mam czasu się zastanawiać , muszę działać! Na początek
    najlepiej pójść do kogoś kogo znam."
    rose " Emily... jestem pewna , że znajdę ją w kwiaciarni"
    hide rose_sad
    scene bg_miasto
    show rose at left with dissolve
    narrator "Rose stanęła przed kwiaciarnią . Przez szybę mogła dostrzec
    Emily układającą bukiety"
    rose "Tak jak myślałam Emily jest dzisiaj w pracy. Tylko co ja jej
    powiem? Jak tak teraz o tym myślę to nie znam Emily za dobrze i nie
    jest ona zbyt towarzyską osobą . Nie mogę jej  od tak poprosić by
    poszła ze mną"
    narrator "Rose spojrzała na pistolet z nabojami usypiającymi , który
    dostała z listem jednak natychmiast go schowała"
    rose " Nie, nie, nie."
    rose " Nawet o tym nie myśl! Jeśli muszę to zrobić ... Jeśli muszę
    ich zabrać to nie w ten sposób!"
    narrator "Podburzona natłokiem emocji Rose wchodzi do kwiaciarni"

    show emily at right with dissolve
    show rose_looking_at_mira
    narrator ""


    return
    label GotoRutger:
    play music city_sound
    rose "Rutger... Nie mam bladego pojęcia kim on jest ani gdzie go
    znaleść"
    hide rose_sad
    scene bg_miasto
    show rose at right with dissolve
    narrator " Nie wiedząc co ze sobą zrobić Rose zaczęła chodzić po
    mieście i pytać każdego kogo spotka o tajemniczego mężczyznę jednak
    nikt nie miał pojęcia kim jest Rutger Krause"
    rose "Jak to jest możliwe, że nikt o nim nie słyszał? Przecież w
    tym mieście każdy zna każdego..."
    narrator " Rose zaczęła błąkać się bez celu rozmyślając o wszystkich
    czarnych scenariuszach,które mogłyby się wydarzyć jeśli nie wykona zadania."
    narrator "Sama myśl o konsekwencjach jakie nastąpią, gdy poniesie porażkę
    napełniała ją takim strachem, że nie była w stanie myśleć o tym
    co czeka osoby , których imiona są na liście "
    rose " Co jeśli mi się nie uda ... całe miasto i istota, na której
    zbudowaliśmy naszą enklawę......"
    narrator "Rose ze spuszczoną głową idzie przed siebie"
    narrator "Głębokie rozmyślanie przerywa jej odgłos klaszczącego
    tłumu. Spoglądając w górę ujrzała małą scenę, na której właśnie
    skończył się występ Luisa"
    rose "Chwila, czy Luis nie jest czasem na liście?"
    rose "Nie ma czasu na myślenie muszę się wziąć w garść!"
    narrator "Rose szybko biegnie w kierunku Luisa, który właśnie
    schodzi ze sceny."
    show luis at left with dissolve
    narrator ""
