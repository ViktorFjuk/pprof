# pprof
pprof for sem02 is-105 uia

Bevis for oppgave til seminar



Profile001.svg tilhører wordcount01 med profiltypen:  defer profile.Start(profile.CPUProfile, profile.ProfilePath(".")).Stop()

Profile002.svg tilhører wordcount01 med profiltypen:  defer profile.Start(profile.MemProfile, profile.ProfilePath(".")).Stop()

Profile003.svg tilhører wordcount01 med profiltypen: defer profile.Start(profile.MemProfile, profile.MemProfileRate(1), profile.ProfilePath(".")).Stop()


Profile004.svg tilhører wordcount02 med profiltypen: defer profile.Start(profile.CPUProfile, profile.ProfilePath(".")).Stop()

Profile005.svg tilhører wordcount02 med profiltypen: defer profile.Start(profile.MemProfile, profile.ProfilePath(".")).Stop()

Profile006.svg tilhører wordcount02 med profiltypen:  defer profile.Start(profile.MemProfile, profile.MemProfileRate(1), profile.ProfilePath(".")).Stop()


Profile007.svg tilhører wordcount03 med profiltypen: defer profile.Start(profile.CPUProfile, profile.ProfilePath(".")).Stop()

Profile008.svg tilhører wordcount03 med profiltypen: defer profile.Start(profile.MemProfile, profile.ProfilePath(".")).Stop(

Profile009.svg tilhører wordcount03 med profiltypen :  defer profile.Start(profile.MemProfile, profile.MemProfileRate(1), profile.ProfilePath(".")).Stop()
