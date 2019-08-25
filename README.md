# web-video-monitor

Purpose is to:

1. take video from a newscast
2. Use OpenCV to process the video. 
3. Monitor any still images for more than 3 minutes.
4. If still for more than 3 minutes, send email altering that there is an issue. 
5. End script after that newscast is over. 

Good to have:
1. Scan tv listing using Python to see when the next newscasts are airing.
  This would be ideal since there are special events that might occur pre-empting a show like State of the Union
  from the normal scheduled times that you can hardcode into this item.

2. Trigger script to run at this time.
 Obviously, if a sports game runs a bit late this will affect timing but should still see motion being made on 
 livestream so it <b><i>shouldn't</i></b> trigger an email. 
