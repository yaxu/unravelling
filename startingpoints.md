

# Ge Wang

For me, I started working on ChucK in 2002 (shortly after I got to Princeton as as PhD student), partially with the idea to make it an "on-the-fly" language -- reflecting both a personal preference to make things real-time when possible, and an aesthetic curiosity about programming languages that can be used in a "build it as you run it" manner. The temporal determinism and concurrency mechanisms also came about as explorations into designing ChucK, somewhat independently of on-the-fly, although they certainly influence how one live codes in ChucK.  The interest in real-time (and an "hyper" real-time awareness that seems to accompany live programming) can be traced to undergrad where I wrote a lot of real-time graphics and some music/audio software, which in turn may have been from engaging with both musical instruments and video games (two very real-time interactions) since a young age.

# Julian Rohrhuber

interesting question, about the air. Isn’t it always afterwards, that you recognise what you should have found obvious? In any case, looking back, it is indeed rather strange that live coding, and even simply interactive programming, wasn’t obvious at all. A bit of history we have written down for the Dagstuhl publication, and also the first readme paper has some clues, but maybe together we find a trace of what was it that made it all occur about around that same time.

I have to admit that for me, the basic idea came through a misunderstanding. Some time in the nineties, I visited Iannis Zannos’ lab, and he showed me supercollider: a terse little formula that made a pure sine tone fascinated me indefinitely. After a year or so, I started to write programs on paper, because I had no computer. I finally got supercollider in 1997, and when I had running in the lab of the art academy, I was perhaps a little overly delighted by the possibility of actually writing programs, and misread the readme that said somewhere (I dug it up now): “You can read and compile text at runtime.” I thought that this meant that changes in code would be reflected in changes in sound, so that you could “play" the text. Despite my interest in math and sound, I had not the slightest software engineering background, otherwise I would have understood what it really meant.

While you couldn’t program live, as we understand it today, with the initial versions of sc2, the particular computer science tradition which it inherited (literate programming, REPL etc.) was a strong impulse in this direction. The idea of taking code as interface somehow wasn’t generally self-evident nevertheless, and once it had become possible in principle (in some of the versions of sc2, I suspect it was introduced in 2.2.2 in order to be able to read files while playing sounds) it wasn’t even mentioned; over the following years it remained a repeated effort to keep this possibility alive, especially around 2001. This is how I realised that even wanting to code live isn’t that obvious after all.

The fact that running code could work like reading code (select and eval, and not compiling a whole file), made it possible to think of the GUI as obstruction for the interaction with a program (rather than the other way round). Because I was always late in preparing my code for the internet-radio broadcasts we did, I tended to program "on air”, though not “live". Being in a broadcast “studio”, half public, half hidden, made that possible. Giving workshops for other students together with Renate, teaching and experimenting with code provided a similar semi-official space. More than anything else, it was such exchange among friends that made it possible to really think in a certain way.

In the fluxus tradition of the art academy, there was a lot of conversational art with computers (e.g. email art), and happenings that involved any form of typography, text or chat was quite common. E.g. hypercard was used a lot. Projectors had just became affordable for the rather low budgets in this field, and projection was associated with art, so projecting code in public spaces certainly fell within the established paradigm. Nevertheless at that time, the stage was something one tended to try to overcome and to weaken, e.g. by participatory installations, or moving into a dark corner as a techno DJ. Virtuosity was rather suspicious. So to project code on stage, was after all not such an obvious thing to do, not so much because code was weird, but because the stage was weird. One of the reasons why hacking in nightclubs became important.

Please excuse the rather long ramblings. So I better leave out the philosophical and media-theoretical aspects here. So what was in the air? I suspect that it was a merge of cultures that led to a rather strange mix of expertise and ignorance, technical development and economy, made it possible exactly then. It had to be found out some time, after all. But I’m really curious to hear about more experiences ...

# Nick Collins

Thanks for the beautifully self-reflective email, Julian!

My primary recollection would centre on James McCartney's SuperCollider workshop at ICMC 2000 in Berlin, and running his presentation including of course the code examples within SuperCollider 2. Andrew Brown has an edited issue of Journal of Music Technology and Education coming out soonish with a paper by me from the pedagogical perspective ("Live Coding and Teaching SuperCollider") and therein I definitely credit JMC with inspiration.

sc-users mailing list circa 2001 had a certain amount of inspirational live coding in the air based on the Tspawn hack, with Julian's efforts around jitlib primary.

best

# Fabrice Mogini

I remember that in early version of SC2 I had to wait for ages until my newly edited sequence would reach the place where I could hear the new part I had just worked on....so I was really keen on getting to try out new code instantly...

I was using a GUI in SC2 to write a function as String, which could be evaluated using .interpret. That worked well; I remember showing this to felix when he once stayed over my place in London and he said he was using this also. Also in SC2, using global variables inside a function also worked and i think several people where doing it; I did a tutorial with a handout called 'live coding' which I taught at my London course in Hackney and that I also shared when I participated the the IDM school London as a guest lecturer. 

When Julian implemented Just in Time library, it really solved a lot of things and made everything easier especially....and finally SC Server was designed differently and made it very accessible.

# Nick

I wonder if the perl written live at that event was a modified script then run at command line a la early alexslub performance, rather than a quicker paced live code interaction (not to deny that some sort of concert programming was underway!). Strange that ade's pure events not mentioned more explicitly...

