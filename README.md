

# Recalculated pp

[Leaderboards sorted by total pp](https://github.com/Antaruv/pp-recalc/blob/master/pp.markdown)  
[Leaderboards sorted by aim pp](https://github.com/Antaruv/pp-recalc/blob/master/aim.markdown)  
[Leaderboards sorted by speed pp](https://github.com/Antaruv/pp-recalc/blob/master/speed.markdown)  
[Leaderboards sorted by acc pp](https://github.com/Antaruv/pp-recalc/blob/master/acc.markdown)  

---

[Top 1000 scores by total pp](https://github.com/Antaruv/pp-recalc/blob/master/scorestotal.markdown)  
[Top 1000 scores by aim pp](https://github.com/Antaruv/pp-recalc/blob/master/scoresaim.markdown)  
[Top 1000 scores by speed pp](https://github.com/Antaruv/pp-recalc/blob/master/scoresspeed.markdown)  
[Top 1000 scores by acc pp](https://github.com/Antaruv/pp-recalc/blob/master/scoresacc.markdown)  

---

This is a set of lists of ranks (both for scores and players) based on recalculations done approximately the same way osu!tp did them. The strain values for every map and mod combination necessary were calculated with oppai. The pp calculations themselves were rewritten into Ruby for my personal ease of use. The scores won't all be accurate with what oppai says or what the website says, but they should all be within realm of acceptable error.

All of the top 10k players' top 100 performances were taken through osu's API. Some scores are missing in final calculations for various reasons, but very few people are affected in any meaningful way by this.

Each individual score consists of an aim, speed and accuracy rating. This was true for osu!tp, and is true for pp now. The biggest difference is that on osu!tp, these three were kept seperate until the very end. Every player's top 100 scores have been recalculated into their respective aim/speed/acc pp's. These have then been sorted 3 times for by their aim/speed/acc values, and for each list of sorted pp's, they have been weighted using **0.9^n**. This 0.9 is notable. Online, the scores are weighted 0.95^n, but on osu!tp they appear to have been weighted following 0.85^n. **The weight formula was therefore just decided by averaging out the 0.85 and 0.95.**

# Your scores

You can see there's the top 1000 scores in each field, but what about all of your own scores? You can download those all from [http://puu.sh/popb4.zip](http://puu.sh/popb4.zip) (~68MB). In this zip file, you'll find every single score used to calculate the total pp's, all seperated by player and ordered in descending order. These text files are not intended to be read from a text editor, and can be copy-pasted into, say, excel. The format of each of the scores is:  
"play details [tab] total pp [tab] aim pp [tab] speed pp [tab] acc pp".

---

**If you have any questions, please [post in the recent thread](https://www.reddit.com/r/osugame/comments/4nm4ct/top_10k_players_aim_speed_and_acc_pp_like_osutp/) or [message me on reddit.](https://www.reddit.com/message/compose/?to=Purper)**
