# Automatic Keywords Highlighter

<img src="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/src/icons/icon128.png" align="right" style="padding-left: 10px;" />

Set a list of keywords and *Automatic Keywords Highlighter* will automatically
highlight them on any web page you visit. The icon shows you how often a keyword
was highlighted on the current page.

Instead of searching for the interesting bits of a web page, let *Automatic
Keywords Highlighter* show them to you instantly. Simply type in a list of
keywords and pick your favourite highlighter color.

Stop searching! Use *Automatic Keywords Highlighter!*

## Installation

You can install *Automatic Keywords Highlighter* directly from the
[Chrome Web Store](https://chrome.google.com/webstore/detail/automatic-keywords-highli/gcpknobcboilhnacklgmaamlcnblneoi).

## Screenshots

<a href="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/google-webstore/screenshot1.jpg" target="_blank"><img src="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/google-webstore/screenshot1.jpg" width="150" border="0" /></a>
&nbsp;
<a href="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/google-webstore/screenshot2.jpg" target="_blank"><img src="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/google-webstore/screenshot2.jpg" width="150" border="0" /></a>
&nbsp;
<a href="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/google-webstore/screenshot3.jpg" target="_blank"><img src="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/google-webstore/screenshot3.jpg" width="150" border="0" /></a>
&nbsp;
<a href="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/google-webstore/screenshot4.jpg" target="_blank"><img src="https://raw.githubusercontent.com/wrzlbrmft/chrome-keywords-highlighter/master/google-webstore/screenshot4.jpg" width="150" border="0" /></a>
&nbsp;

## How to Contribute

Feel free to join and help me improve this extension. Here are a few ideas:

* Translate it into other languages.
* Port it to other browsers like
[Mozilla Firefox](https://www.mozilla.org/firefox) or
[Internet Explorer](http://windows.microsoft.com/internet-explorer/).

### Getting the Source Code

You can download the latest source code as a [ZIP
file](https://github.com/wrzlbrmft/chrome-keywords-highlighter/archive/master.zip)
or use Git:

```
git clone https://github.com/wrzlbrmft/chrome-keywords-highlighter.git
```

### Testing in Google Chrome

If you want to test your contributions in Chrome, you can load the extension
directly from its source directory. First, download the source code as described
above. Then open Chrome and follow these steps:

1. Visit `chrome://extensions`.
2. Make sure that the *Developer mode* is active (checkbox in the upper-right
corner).
3. Click on *Load unpacked extension...*.
4. Navigate into the `src` directory of the source code and select it.

Whenever you updated a file of the extension you have to reload it in Chrome.
To do so, simply visit `chrome://extensions` again and hit *Ctrl+R*.

## Build Instructions

Actually, there is not much to build unless you want to write your own extension
based on this one. For that, I added a buildfile for
[Apache Ant](http://ant.apache.org/), see `build.xml`. It helps you create the
ZIP file which you have to upload to the
[Chrome Developer Dashboard](https://chrome.google.com/webstore/developer/dashboard).

To build the ZIP file, navigate into the top directory of the extension and run

```
ant zip
```

or simply

```
ant
```

**NOTE:** Make sure you already have a private key, if not see *Private Key*.

The ZIP file is then located in the `build` directory.

To clean up after a build, run

```
ant clean
```

This will not delete the private key file of course.

### Private Key

In order to build a ZIP file using Ant, you have to have a private key for the
extension. To create one follow
[these instructions](https://developer.chrome.com/extensions/packaging#creating).

Rename the private key file to `key.pem` and make sure it is in the top
directory of the extension. You do not need the `.crx` file, so it can be
deleted.

### Versioning

The version number of the extension is maintained in the Ant buildfile
`build.xml` and only copied to `manifest.json` of the ZIP file during the build
process.

To change the version number, open `build.xml` and edit this
line:

```xml
<property name="version" value="0.1.0" />
```

## License

This software is distributed under the terms of the
[GNU General Public License v3](https://www.gnu.org/licenses/gpl-3.0.en.html).

Based on an earlier Chrome extension named
*[Keywords Highlighter](https://code.google.com/p/keywords-highlighter/)*
([Chrome Web Store](https://chrome.google.com/webstore/detail/keywords-highlighter/nnfnbecknbhnihnjjbblckanjajgjkkh))
which was also using
[highlight](http://johannburkard.de/blog/programming/javascript/highlight-javascript-text-higlighting-jquery-plugin.html)
by [Johann Burkard](http://johannburkard.de/), both distributed under the terms
of the [MIT License](http://opensource.org/licenses/MIT).

The icon is taken from the
*[Soft Scraps Icons](http://www.iconarchive.com/show/soft-scraps-icons-by-hopstarter.html)*
icons pack designed by [Jojo Mendoza](https://twitter.com/hopstarter)
distributed under the terms of the
[CC BY-NC-ND 4.0](http://creativecommons.org/licenses/by-nc-nd/4.0/) license.



```
Jesus, 4r5e, 50 yard cunt punt, 5h1t, 5hit, a_s_s, a2m, a$$, a55, a$$hole, a55hole, adult, aeolus, ahole, amateur, anal, anal impaler , anal leakage , analprobe, anilingus, anus, ar5e, areola, areole, arian, arrse, arse, arsehole, aryan, ass, ass fuck , ass hole, ass-fucker, assbang, assbanged, assbangs, asses, assfuck, assfucker, assfukka, assh0le, asshat, assho1e, asshole, assholes, assmaster, assmucus , assmunch, asswhole, asswipe, asswipes, autoerotic, azazel, azz, b!tch, b00bs, b17ch, b1tch, babe, babes, ballbag, ballsack, bang, bang (one's) box , bangbros, banger, bareback, barf, bastard, bastards, bawdy, beaner, beardedclam, beastial, beastiality, beatch, beater, beaver, beef curtain , beer, beeyotch, bellend, beotch, bestial, bestiality, bi+ch, biatch, big tits, bigtits, bimbo, bimbos, birdlock, bitch, bitch tit , bitched, bitcher, bitchers, bitches, bitchin, bitching, bitchy, bloody, blow, blow job, blow me , blow mud , blowjob, blowjobs, blue waffle , blumpkin , bod, bodily, boink, boiolas, bollock, bollocks, bollok, bone, boned, boner, boners, bong, boob, boobies, boobs, booby, booger, bookie, booobs, boooobs, booooobs, booooooobs, bootee, bootie, booty, booze, boozer, boozy, bosom, bosomy, bowel, bowels, bra, brassiere, breast, breasts, buceta, bugger, bukkake, bull shit, bullshit, bullshits, bullshitted, bullturds, bum, bung, bunny fucker, bust a load , busty, butt, butt fuck, butt fuck , buttfuck, buttfucker, butthole, buttmuch, buttplug, c-0-c-k, c-o-c-k, c-u-n-t, c.0.c.k, c.o.c.k., c.u.n.t, c0ck, c0cksucker, caca, cahone, cameltoe, carpet muncher, carpetmuncher, cawk, cervix, chinc, chincs, chink, choade , chode, chodes, chota bags , cipa, cl1t, climax, clit, clit licker , clitoris, clitorus, clits, clitty, clitty litter , clusterfuck, cnut, cocain, cocaine, cock, cock pocket , cock snot , cock sucker, cock-sucker, cockblock, cockface, cockhead, cockholster, cockknocker, cockmunch, cockmuncher, cocks, cocksmoker, cocksuck, cocksucked, cocksucker, cocksucking, cocksucks, cocksuka, cocksukka, coital, cok, cokmuncher, coksucka, commie, condom, coon, coons, cop some wood , corksucker, cornhole , corp whore , cox, crabs, crack, cracker, crackwhore, crap, crappy, cum, cum chugger , cum dumpster , cum freak , cum guzzler , cumdump , cummer, cummin, cumming, cums, cumshot, cumshots, cumslut, cumstain, cunilingus, cunillingus, cunnilingus, cunny, cunt, cunt hair , cunt-struck , cuntbag , cuntface, cunthunter, cuntlick, cuntlick , cuntlicker, cuntlicker , cuntlicking , cunts, cuntsicle , cut rope , cyalis, cyberfuc, cyberfuck , cyberfucked, cyberfucker, cyberfuckers, cyberfucking, d0ng, d0uch3, d0uche, d1ck, d1ld0, d1ldo, dago, dagos, dammit, damn, damned, damnit, dawgie-style, dick, dick hole , dick shy , dick-ish, dickbag, dickdipper, dickface, dickflipper, dickhead, dickheads, dickish, dickripper, dicksipper, dickweed, dickwhipper, dickzipper, diddle, dike, dildo, dildos, diligaf, dillweed, dimwit, dingle, dink, dinks, dipship, dirsa, dirty Sanchez , dlck, dog-fucker, doggie style, doggie-style, doggiestyle, doggin, dogging, doggy-style, dong, donkeyribber, doofus, doosh, dopey, douch3, douche, douchebag, douchebags, douchey, drunk, duche, dumass, dumbass, dumbasses, dummy, dyke, dykes, eat a dick , eat hair pie , ejaculate, ejaculated, ejaculates, ejaculating, ejaculatings, ejaculation, ejakulate, enlargement, erect, erection, erotic, essohbee, extacy, extasy, f u c k, f u c k e r, f_u_c_k, f-u-c-k, f.u.c.k, f4nny, facial , fack, fag, fagg, fagged, fagging, faggit, faggitt, faggot, faggs, fagot, fagots, fags, faig, faigt, fanny, fannybandit, fannyflaps, fannyfucker, fanyy, fart, fartknocker, fat, fatass, fcuk, fcuker, fcuking, feck, fecker, felch, felcher, felching, fellate, fellatio, feltch, feltcher, fingerfuck, fingerfucked, fingerfucker , fingerfuckers, fingerfucking, fingerfucks, fist fuck , fisted, fistfuck, fistfucked, fistfucker , fistfuckers, fistfucking, fistfuckings, fistfucks, fisting, fisty, flange, flog the log , floozy, foad, fondle, foobar, fook, fooker, foreskin, freex, frigg, frigga, fubar, fuck, fuck , fuck hole , fuck puppet , fuck trophy , fuck yo mama , fuck-ass , fuck-bitch , fuck-tard, fucka, fuckass, fucked, fucker, fuckers, fuckface, fuckhead, fuckheads, fuckin, fucking, fuckings, fuckingshitmotherfucker, fuckme, fuckmeat , fucknugget, fucknut, fuckoff, fucks, fucktard, fucktoy , fuckup, fuckwad, fuckwhit, fuckwit, fudge packer, fudgepacker, fuk, fuker, fukker, fukkin, fuks, fukwhit, fukwit, fux, fux0r, fvck, fxck, g-spot, gae, gai, gang-bang , gangbang, gangbang , gangbanged, gangbangs, ganja, gassy ass , gay, gaylord, gays, gaysex, gey, gfy, ghay, ghey, gigolo, glans, goatse, god, god damn, god-dam, god-damned, godamn, godamnit, goddam, goddammit, goddamn, goddamned, goldenshower, gonad, gonads, gook, gooks, gringo, gspot, gtfo, guido, h0m0, h0mo, ham flap , handjob, hard on, hardcoresex, he11, hebe, heeb, hell, hemp, heroin, herp, herpes, herpy, heshe, hitler, hiv, hoar, hoare, hobag, hoer, hom0, homey, homo, homoerotic, homoey, honky, hooch, hookah, hooker, hoor, hootch, hooter, hooters, hore, horniest, horny, hotsex, how to kill, how to murdep, hump, humped, humping, hussy, hymen, inbred, incest, injun, j3rk0ff, jack-off, jackass, jackhole, jackoff, jap, japs, jerk, jerk-off, jerk0ff, jerked, jerkoff, jism, jiz, jizm, jizz, jizzed, junkie, junky, kawk, kike, kikes, kill, kinky, kinky Jesus , kkk, klan, knob, knob end, knobead, knobed, knobend, knobhead, knobjocky, knobjokey, kock, kondum, kondums, kooch, kooches, kootch, kraut, kum, kummer, kumming, kums, kunilingus, kwif , kyke, l3i+ch, l3itch, labia, lech, LEN, leper, lesbians, lesbo, lesbos, lez, lezbian, lezbians, lezbo, lezbos, lezzie, lezzies, lezzy, lmao, lmfao, loin, loins, lube, lust, lusting, lusty, m-fucking, m0f0, m0fo, m45terbate, ma5terb8, ma5terbate, mafugly , mams, masochist, massa, master-bate, masterb8, masterbat*, masterbat3, masterbate, masterbating, masterbation, masterbations, masturbate, masturbating, masturbation, maxi, menses, menstruate, menstruation, meth, mo-fo, mof0, mofo, molest, moolie, moron, mothafuck, mothafucka, mothafuckas, mothafuckaz, mothafucked, mothafucker, mothafuckers, mothafuckin, mothafucking, mothafuckings, mothafucks, mother fucker, mother fucker , motherfuck, motherfucka, motherfucked, motherfucker, motherfuckers, motherfuckin, motherfucking, motherfuckings, motherfuckka, motherfucks, mtherfucker, mthrfucker, mthrfucking, muff, muff puff , muffdiver, murder, mutha, muthafecker, muthafuckaz, muthafucker, muthafuckker, muther, mutherfucker, mutherfucking, muthrfucking, n1gga, n1gger, nad, nads, naked, napalm, nappy, nazi, nazism, need the dick , negro, nigg3r, nigg4h, nigga, niggah, niggas, niggaz, nigger, niggers, niggle, niglet, nimrod, ninny, nipple, nob, nob jokey, nobhead, nobjocky, nobjokey, nooky, numbnuts, nut butter , nutsack, nympho, omg, opiate, opium, oral, orally, organ, orgasim , orgasims , orgasm, orgasmic, orgasms , orgies, orgy, ovary, ovum, ovums, p.u.s.s.y., p0rn, paddy, paki, pantie, panties, panty, pastie, pasty, pawn, pcp, pecker, pedo, pedophile, pedophilia, pedophiliac, pee, peepee, penetrate, penetration, penial, penile, penis, penisfucker, perversion, peyote, phalli, phallic, phonesex, phuck, phuk, phuked, phuking, phukked, phukking, phuks, phuq, pigfucker, pillowbiter, pimp, pimpis, pinko, piss, piss-off, pissed, pisser, pissers, pisses , pissflaps, pissin, pissing, pissoff, pissoff , pms, polack, pollock, poon, poontang, poop, porn, porno, pornography, pornos, pot, potty, prick, pricks, prig, pron, prostitute, prude, pube, pubic, pubis, punkass, punky, puss, pusse, pussi, pussies, pussy, pussy fart , pussy palace , pussypounder, pussys, puto, queaf, queaf , queef, queer, queero, queers, quicky, quim, r-tard, racy, rape, raped, raper, rapist, raunch, rectal, rectum, rectus, reefer, reetard, reich, retard, retarded, revue, rimjaw, rimjob, rimming, ritard, rtard, rum, rump, rumprammer, ruski, s hit, s_h_i_t, s-h-1-t, s-h-i-t, s-o-b, s.h.i.t., s.o.b., s0b, sadism, sadist, sandbar , sausage queen , scag, scantily, schizo, schlong, screw, screwed, screwing, scroat, scrog, scrot, scrote, scrotum, scrud, scum, seaman, seamen, seduce, semen, sex, sexual, sh!+, sh!t, sh1t, shag, shagger, shaggin, shagging, shamedame, shemale, shi+, shit, shit fucker , shitdick, shite, shiteater, shited, shitey, shitface, shitfuck, shitfull, shithead, shithole, shithouse, shiting, shitings, shits, shitt, shitted, shitter, shitters, shitting, shittings, shitty, shiz, sissy, skag, skank, slave, sleaze, sleazy, slope , slut, slut bucket , slutdumper, slutkiss, sluts, smegma, smut, smutty, snatch, sniper, snuff, sodom, son-of-a-bitch, souse, soused, spac, sperm, spic, spick, spik, spiks, spooge, spunk, steamy, stfu, stiffy, stoned, strip, stroke, stupid, suck, sucked, sucking, sumofabiatch, t1t, t1tt1e5, t1tties, tampon, tard, tawdry, teabagging, teat, teets, teez, terd, teste, testee, testes, testical, testicle, testis, thrust, thug, tinkle, tit, tit wank , titfuck, titi, tits, titt, tittie5, tittiefucker, titties, titty, tittyfuck, tittyfucker, tittywank, titwank, toke, toots, tosser, tramp, transsexual, trashy, tubgirl, turd, tush, tw4t, twat, twathead, twats, twatty, twunt, twunter, ugly, undies, unwed, urinal, urine, uterus, uzi, v14gra, v1gra, vag, vagina, valium, viagra, virgin, vixen, vodka, vomit, voyeur, vulgar, vulva, w00se, wad, wang, wank, wanker, wanky, wazoo, wedgie, weed, weenie, weewee, weiner, weirdo, wench, wetback, wh0re, wh0reface, whitey, whiz, whoar, whoralicious, whore, whorealicious, whored, whoreface, whorehopper, whorehouse, whores, whoring, wigger, willies, willy, womb, woody, wop, wtf, x-rated, xrated, xxx, yeasty, yobbo, zoophile
```
