### Notes from class 
RAND founded in 1946, for the airforce. a think tank. They all recognized that robust communications were necessary to survive (ha) a nuclear war/error. But how to achieve this was up in the air. This was the quesiton that engineer Paul Baran started exploring from 1959

Baran's original system was the simplest system:
go/no go
via am radio to commanders in the field: nuke or no nuke.

Military wants rather more than this; back to drawing board.

|Regular Communication | 'Distributed Communication'
|------------------------|------------------------------|
| hierarchy - call to local office <-> regional <-> national <-> regional and back | nodes and switches |
| destroy local/regional/national office, comms cut off | destroy node, still other paths|

Controlling data flow - "message switching"

<li>&shy;<!-- .element: class="fragment" data-fragment-index="1" -->think &#39;post office&#39;: one integral message, label w/ origin and destination, passed from station to station</li>

<li>&shy;<!-- .element: class="fragment" data-fragment-index="2" -->each station (post office) holds on to it until it can be forwarded to the next node/destination</li>

<li>&shy;<!-- .element: class="fragment" data-fragment-index="3" -->telegraph system does this. At first manually, by 1960s, using computers to store/route messages</li>

<li>&shy;<!-- .element: class="fragment" data-fragment-index="4" -->these also lets you even out the flow - messages can be stored until there&#39;s space to move it (makes the line more profitable)</li>

<li>&shy;<!-- .element: class="fragment" data-fragment-index="5" -->Baran&#39;s system isn&#39;t hierarchical; key is that the switches can reroute as necessary</li>
<p>a distributed communications network, preceeding Baran&#39;s work! AT&amp;T and the Army; military voice network built on top of the existing civilian network. Went online with 10 nodes in 1964. Eventually extended around the world. Continues in service until the 1990s</p>

<p>AT&amp;T &#39;hardened&#39; exchanges, and connected things up in a grid, in contrast to hierarchical civilian lines. Distributed nodes, but those nodes centrally controlled, telephone switches. Like a traffic control system. Manually re-routing things as necessary. Baran&#39;s system control itself was distributed: the node was a computer making its own decision about where to send the message next.</p>

<p>Computerizing the switches and giving them the autonomy to decide where to route things: that&#39;s the big idea. nodes along the line can regenerate the signal; in the analogue approach, this would actual degrade the signal.</p>

<p>People trained in telephony scoffed at Baran.</p>
