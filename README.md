# LingoLang

<br />
<br />

<!-- Good programming music: https://www.youtube.com/watch?v=CLeZyIID9Bo -->


![LingoLang](https://github.com/CatX711/LingoLang/assets/104099162/36abdc0d-071e-4704-8f1c-ae4e6f98961e)





<br />




>Ah yes, another adition to the multitude of pointless creations I own.
>
>  *- Daniel*




<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

<h2>Hello World!</h2>

<br />
<br />
Hello world. Welcome to this new programming language book! Well, technically this should be more of the "Official Docs", but did you see how many words GreetLang+ got to? Yeah, 2000 words is pretty much a book.
<br />
I've been yearning to get back into the programming world recently, but I haven't really known how. The thing is, I've been doing a lot of writing. So... okay, I get it, just let me have some fun ;) 

<br />
<br />
<br />

According to feedback the GreetLang+ book was a lot more verbose, containing long and drawn out explinations for most of it's features. But I can't lie, that was the point. That book was a way to test my programming + writing skills and imagination. It was assuming you were a beginner, which most of the people in my family and friend group are. However, due to the lack of interest in programming, and quite frankly, the humongous size of it, I'm guessing around 4 people only ever saw it. Me, my dad, my mum, and perhaps some random coder browsing the interwebs.

<br />
<br />

This, however, aims to be more concise, and just for me or any other developers who find my work impressive to read without the 2000 word's worth of detail.



<br />
<br />
<br />
<br />

<h2>Basic Syntax</h2>

<br />
<br />

<p>Lingo is a server side language built to be easier to understand than HTML. It has a simple syntax, easy to learn concepts, and a beginner friendly UI.</p> <br />

Let's start with printing a simple `Hello there!`. We will need to send out a request to the server to output our text into the terminal. Keep in mind that we are not currently on any website.


<br />
<br />

```JS
--Req("Hello there!")
``` 

<br />
<br />

By using `--Req` we make our request. Isn't that convenient? <br />
Another useful thing to know is how to make comments. Comments are pieces of text in your code that serve as info for anyone reading it. You probably know that alredy. So, how do you comment in Lingo?

<br />

```JS
;Aloha! use the semicolon: ;   to create comments. Here's an example:


--Req("Cake makes me feel supercalifragilisticexpialidocious!") ;Change word, far too complex.
```

<br />
<br />

<p>If you want your terminal to look very pretty, you can still use the styling tags like <h> from HTML that are normally restricted for the website code. <br />
That means your terminal could end up looking like this when you run your program, if you so wish: </p>

<br />

![3HNXH-3307957011](https://github.com/CatX711/LingoLang/assets/104099162/7b7470e5-5776-4984-b346-4dc466f22d2a)


<br />
<br />
<br />

Let's go over styling, shall we?


<br />
<br />
<br />
<br />

<h2>Styling</h2>

<br />
<br />

So, how do we style our terminal text? <br />
While using `--Req` we can define size, font, colour, etc.

<br />

```JS
--Req(size=2, font=Comic_Sans, colour=Brilliant_Blue, "I love pizza!")
```

<br />
<br />

You can see here how we define size, font and colour all in one Req! No need for extra lines, just plain old simplicity. `Note: seperate different things you want to alter with a comma: ,   and when changing the size, font or colour, never use spaces, substitute them with underscores: _`

<br />

Keep in mind, instead of having independant header tags for the terminal, the only method of changing the size of a string is the `size` variable within the Req function. For less confusion and time spent refreshing your website every time you change the `size=`, instead you will have a version of <h> tags from HTML, but only when working with code for a website. So, `size` is for terminal strings only. Got it?

<br />
<br />
<br />
<br />

<h2>Website Building</h2>

<br />
<br />

Now we get on to the juicy stuff. Website building is a lot easier than you expect with Lingo. <br />
First, secure a domain, with it's own IP address. `E.g 184.212.251.94`

<br />

Open up a fresh Lingo-gram (Lingo Program/File) and write the following:

<br />
<br />

```JS
--domainIp = 184.212.251.94
```

Great! You've just told your server what website it has to contact. <br />

```JS
--domainIp = 184.212.251.94
--tabName = My Lovely Website
```

<br />

`tabName` is what you want to be displayed on your website's tab. E.g the name on the tab you're on right now is: `CatX711/Lingolang/Ah yes, another adition to the multitude of pointless creations I own. ` Or `LingoLang/README.md at main ` depending on how you're reading this. Sure, that's not the best example, but here's one that's easier to understand: Go on YouTube or Google, and be on a fresh page. For Google, you simply have the word 'Google' displayed in the tab. The same goes for youtube.

<br />
<br />

![Screenshot 2023-09-09 133842](https://github.com/CatX711/LingoLang/assets/104099162/722c0286-bf13-48d8-aee8-0997a70d5b73)

![Screenshot 2023-09-09 133921](https://github.com/CatX711/LingoLang/assets/104099162/8054ae1e-ce04-45ab-9822-20f4e3e3483a)

<br />

(Snag a quick look at my own website's tab name if you want another example: https://resilient-gumption-7417cf.netlify.app/)

<br />
<br />

You can also put your own icon there, if you wish.

<br />

```JS
--domainIp = 184.212.251.94
--tabName = My Lovely Website

--tabIcon(src=./Pictures/CatImage03.png)
```

<br />

What does that mean? Well, that's a way to put a tiny LingoLang icon in the tab bar. `scr` is the image source, aka where it's stored in your computer. The server will find this in your computer and make a duplicate for it's own, before displaying it to anyone else visiting your website. The way to access an image is: `.` to exit any other repositories you may be in, followed by `/Foldername` (change foldername to the actual name of the folder your image is in, and in my case, the folder storing my image is named Pictures), and `/Imagename` (do the same here). Finally, follow that by the file's type. For example, `.png` for a png file.

<br />
<br />

The complete formula is: `./Foldername/Imagename.type`

<br />
<br />

Also, please note that the icon has a set size and any images that have a lot of information will have lower resolution when packed into a smaller space.

<br />
<br />
<br />

So, now your website should be a blank page. Let's write something! The default text is going to be a serif font, Times New Roman, however, if you do not like that font you can change it in the code by defining the font family using `--fontFamily = `

<br />

```JS
;Prefiguration
--domainIp = 184.212.251.94
--tabName = My Lovely Website
--tabIcon(src=./Pictures/CatImage03.png)

--fontFamily = Sans_Serif, Noto_Sans_Linear_B, Comic_Sans ;comic sans is the last resort 😬

;Website code:

```

<br />

The way font families work is: The first font you put down is the first to be rendered. If your website cannot load that specific font, it will try the next one specified. E.g, if I have two fonts in my font family, 'Papyrus' and 'Roboto', the website would fall back on Roboto if it couldn't load Papyrus.

<br />
<br />

<h1>Construction</h1>

<br />
<br />

Alright, people. Put your hard hats on, because we've moved on from preconfiguration and setting up the website. It's time to do the dirty work, get down on our knees and build it. The easy stuff is over! 

<br />

The starter kit needed for building a website is obviously: How to display text, how to style text, how to arrange the different elements of it, and how to personalise it. <br />
In Lingo the way to create text is through `para` and `header1-6`. Para is paragraph, `p` in HTML, and header is obviously `h`. 

```JS
-header2/"Aloha!"
-para/"I like oranges."
```

<br />
<br />

If you wanted to have, for example, a size 3 header instead of the default size one header (when you just write 'header' and dont specify the size with any number), write `header3`. It's the same with every other size. 




