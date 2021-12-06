# December 6th 2021

## What I finished

I managed to get half of Susan (the last individual) completed before this week and this leaves only a small portion left for later in the future. I have also entered more metadata (painfully, I will explain why later) and this has allowed me to make two graphs. One based on creater of the images showing who is doing the most in Portfolio (CMN's database digitial software) and the second showing/colour coded based on what kingdom the species belong to showing the breadth of what we have digitized at the library. We now have an almost complete graph showing us who has digitized who and what that author is responsible for. This gives the museum a better understanding of what we have done.

## Things I learned

I had never actually worked with/on knowledge graphs before and this was a good opportunity to get familiar with the process of them. I had also never used Gephi before and now I feel like I understand what Gephic can, and more importantly cannot do and how you should approach the software now. I also have a better understanding of what we have actually done at the library in terms of digitization. It turns out that me and Susan had actually digitized the exact same photo on several occasions showing a lack of communication and something should be done to prevent this in the future. Susan retired before I got to CMN so I had no idea what she had actually worked on (neither did my coworkers) and because of this it resulted in photos getting double digitized. However, since I started we have worked harder at making a uniform and more concrete process in entering metadata which has solved this from occuring in the future but I was dealing with legacy data here so I had to deal with the old way and this was interesting as I only know of the consequences that this caused.

## Things I would do differently

Now that I know how Gephi works there are several things I would do differently

1. Create a uniform excel spreadsheet
    * I decided to make the nodes and edges directly in Gephi and that was a mistake
    * At first it was fine but as I wanted to add more catagories to the nodes (columns) this became torture and took me forever. What is worse if I export the table from Gephi and then reimport that same spreadsheet all my edges dissappear. Even if I seperately export the edges I lose the labelling of the nodes which makes the whole thing unusable now. This was a big problem towards the end of the project as I decided to add the taxonomy at the end. That took me ages and had I just made an excel spreadsheet with the taxonomy and done the edges at the end this would have been avoided.
2. Do the Edges last
    * Edges should be done at the end after you have all the nodes in the graph
    * I decided to sort things by creater (myself/Christina and Susan) and then sort them by author. This was a mistake (or at least not the most efficent). I would have been better off sorting it by creater (that was correct) but then doing it by species and creating a seperate excel spreadsheet that I can fill out with the correct taxonomy so I have one universal metadata. That can then by imported into Gephi and you can go back later and do the edges. This would solve the first problem and save time with the constant checking if species were already a node (this happened a lot, and slowed me down).
3. Use Scientific Name
    * I used the common names for species for this graph and I thought at the time this would a) make things easier for me not having to deal with latin and B) make people able to read it. I suspect many people know what a Polar Bear is but if you say Ursus Maritimus at them you will get a confused face starting back at you. With that in mind I did common names (English). The problem is that many species have multiple common names (especially true for freaking plants!!!!!). This was frustrating when dealing with the taxonomy when all I had written down as a common name which might not even be the most commonlly used common name. Because of that issue in future I would just use the scientific name (Latin) and colour code it best for people to see. This after all would most likely be used for scientists and if the public wanted to see this in the future we can simply copy over the data to a new worshop (Gephi is good for this) and swap out the names with a simply search/replace (gephi can also do this)


There might be other things I would have done differently and if I think of any I will continue to expand this list in the future so I can understand why I did/did not do things a certain way. But in future those are the three biggest issues I had and things I would do differently. As this was something I had never done before and on a platform I had never worked on before this is always bound to happen and I am happy that I have learned from this so I know the do and do nots for future. 

(Making a universal excel spreadsheet would also allow for use on Neo4J which is far superiour to this software and I only avoided that one this time because I wanted to avoid making a excel spreadsheet when I already had some to work off with). For future I would
1. make a universal spreadsheet (with all the data already in tact that you want)
2. Make the edges in Gephi
3. Transcribe the edges into an excel spreadsheet
4. Import the spreadsheet into NEO4J using R (which would be possible with a uniform system that I created)
