graph TB
	en1[En]-->en2[Shou]
	en1-->en3[Shin]
		en3[Shin]---en4[No1]
	en1-->en4[No1]
	en1-->en5[Chota]
	en1-->en6[Fujita]
		en6---a7[Matsumura]
	en1-->en7[Matsumura]
	en1-->en8[Ebisu]
		en6[Fujita]---en8[Ebisu]
	en1-->en9[Turkey]
	en1-->en10[Kikurage]

	b1[Caiman]---b2[Nikaido]
	b3["Prof Kasukabe (Haze)"]---|Taught|b4[Dr Vaux]
	b3---|Taught|b9[Ai Coleman]
	b3-->|Pet|b5[Johnson]
	b4---|Brothers|b7[Zeus Vaux]
	b6[Thirteen]-->|Likes|b2
	b1---|"???"|b9[Ai Coleman]


	c1[Kai]-->|Boss|c2[Dokuga]
	c1-->|Boss|c3[Saji]
	c1-->|Boss|c4[Tetsujo]
	c1-->|Boss|c5[Ushishimada]
	c1-->|Boss|c6[Ton]
	c1-->|Boss|c7[Natsuki]
	c1-->|Boss|c8[Risu]
	c1-->|Boss|c9[Yasaka]

	d1[Chidaruma]-->|Creator|d2["Asu (Kawajiri)"]
		d1---|Friends|a1
	d1-->|Creator|d3[Gura-Gura]
		d3-->|Dog|a3
	d1-->|Creator|d4[Haru Kasukabe]
		d4---|Married|b3
	d1---|"???"|d5[Store]
	d1-->|Creator|d6[Dustin]
		d6---|Friends|a4

	e1[Tanba]-->|Boss|e2[Kirion]
	e1-->|Boss|e3[Fukuyama]
	e1-->|Boss|b1

	f1[Aikawa]---|Friends|c8

	b1-->|Killed|a7
	b1---|"???"|f1
	b1---|"???"|c1

    subgraph Tanba's Pies
        od[Tanba]-- Boss --> ro[Kirion]
        od -- Boss --> rw(Fukuyama)
        od -- Boss --> ro2(Caiman)
    end

subgraph Devils
	d1[Chidaruma]-->|Creator|d2["Asu (Kawajiri)"]
		d1---|Friends|a1
	d1-->|Creator|d3[Gura-Gura]
		d3-->|Dog|a3
	d1-->|Creator|d4[Haru Kasukabe]
		d4---|Married|b3
	d1---|"???"|d5[Store]
	d1-->|Creator|d6[Dustin]
		d6---|Friends|a4
end 
