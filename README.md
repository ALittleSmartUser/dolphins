# Dolphin social networks

Two datasets on bottlenose dolphin associations, both converted to GML so that
`networkx.read_gml` loads them the same way.

## data/dolphins_lusseau.gml

Doubtful Sound, New Zealand. 62 dolphins, 159 undirected edges; an edge means
the two animals were seen together more often than expected by chance.
Unweighted.

Lusseau D., Schneider K., Boisseau O.J., Haase P., Slooten E., Dawson S.M.
*The bottlenose dolphin community of Doubtful Sound features a large proportion
of long-lasting associations.* Behavioral Ecology and Sociobiology 54, 396–405
(2003).

File taken as is from the GraphStream project
(`graphstream/gs-gephi/data/dolphins.gml`).

## data/dolphins_florida_social.gml

Cedar Key, Florida, USA. 151 dolphins, 1554 undirected edges; the "socialize"
network out of the four activity networks in the paper. Edge attribute
`weight` (1–5) is the number of times the pair was observed socializing.
Node labels `Dxxx` keep the original animal ids. The graph has two connected
components (149 + 2 animals).

Gazda S., Iyer S., Killingback T., Connor R., Brault S. *The importance of
delineating networks by activity type in bottlenose dolphins (Tursiops
truncatus) in Cedar Key, Florida.* Royal Society Open Science 2(3), 140263
(2015).

Converted from the edge list `mammalia-dolphin-florida-social` distributed by
the Network Data Repository (Rossi R.A., Ahmed N.K., AAAI 2015,
networkrepository.com), original source Animal Social Network Repository
(bansallab.github.io/asnr).
