from gtts import gTTS 
from pygame import mixer
import os
import time
import sys

def slowprintASCII(s):
  for c in s + '\n':
    sys.stdout.write(c)
    sys.stdout.flush()
    time.sleep(1./100)
    
def slowprintM(s):
  for c in s + '\n':
    sys.stdout.write(c)
    sys.stdout.flush()
    time.sleep(1./10)

def popupmsg(msg):
    label = ttk.Label(popup, text=msg, font=NORM_FONT)
    label.pack(side="top", fill="x", pady=10)
    B1 = ttk.Button(popup, text="Okay", command = popup.destroy)
    B1.pack()
    popup.mainloop()

slowprintASCII("""
 __     __     ______     __         ______     ______     __    __     ______        ______   ______        ______   __  __     ______                            
/\ \  _ \ \   /\  ___\   /\ \       /\  ___\   /\  __ \   /\ "-./  \   /\  ___\      /\__  _\ /\  __ \      /\__  _\ /\ \_\ \   /\  ___\                           
\ \ \/ ".\ \  \ \  __\   \ \ \____  \ \ \____  \ \ \/\ \  \ \ \-./\ \  \ \  __\      \/_/\ \/ \ \ \/\ \     \/_/\ \/ \ \  __ \  \ \  __\                           
 \ \__/".~\_\  \ \_____\  \ \_____\  \ \_____\  \ \_____\  \ \_\ \ \_\  \ \_____\       \ \_\  \ \_____\       \ \_\  \ \_\ \_\  \ \_____\                         
  \/_/   \/_/   \/_____/   \/_____/   \/_____/   \/_____/   \/_/  \/_/   \/_____/        \/_/   \/_____/        \/_/   \/_/\/_/   \/_____/                         
																																							   
 ______     ______     __    __     ______   __  __     ______   ______     ______        ______     ______     __     ______     __   __     ______     ______    
/\  ___\   /\  __ \   /\ "-./  \   /\  == \ /\ \/\ \   /\__  _\ /\  ___\   /\  == \      /\  ___\   /\  ___\   /\ \   /\  ___\   /\ "-.\ \   /\  ___\   /\  ___\   
\ \ \____  \ \ \/\ \  \ \ \-./\ \  \ \  _-/ \ \ \_\ \  \/_/\ \/ \ \  __\   \ \  __<      \ \___  \  \ \ \____  \ \ \  \ \  __\   \ \ \-.  \  \ \ \____  \ \  __\   
 \ \_____\  \ \_____\  \ \_\ \ \_\  \ \_\    \ \_____\    \ \_\  \ \_____\  \ \_\ \_\     \/\_____\  \ \_____\  \ \_\  \ \_____\  \ \_\\\\"\_\  \ \_____\  \ \_____\ 
  \/_____/   \/_____/   \/_/  \/_/   \/_/     \/_____/     \/_/   \/_____/   \/_/ /_/      \/_____/   \/_____/   \/_/   \/_____/   \/_/ \/_/   \/_____/   \/_____/ 
																																								   
 ______     __         __  __     ______        __   __   __     _____     ______     ______                                                                       
/\  ___\   /\ \       /\ \/\ \   /\  == \      /\ \ / /  /\ \   /\  __-.  /\  ___\   /\  __ \                                                                      
\ \ \____  \ \ \____  \ \ \_\ \  \ \  __<      \ \ \' /   \ \ \  \ \ \/\ \ \ \  __\   \ \ \/\ \                                                                     
 \ \_____\  \ \_____\  \ \_____\  \ \_____\     \ \__|    \ \_\  \ \____-  \ \_____\  \ \_____\                                                                    
  \/_____/   \/_____/   \/_____/   \/_____/      \/_/      \/_/   \/____/   \/_____/   \/_____/                                                                    
																																									   
	""")

for i in range(3):
	if i==0:
		slowprintM("""\n\nYou there, Yes YOU are you interested in participating in the various hackathons and CTFs,
        coding competitions, or learning code tidbits in general? Then the computer science club is for you!""")
		# ~ time.sleep(3)
		mytext = """You there, Yes YOU are you interested in participating in the various hackathons and CTFs,
					coding competitions, or learning code tidbits in general? Then the computer science club is for you!
				 """
	elif i==1:
		slowprintM("""\n\nNeed more convincing? Just join us for our Arnold C workshop and learn how to code completely in
        arnold schwarzenegger one liners and feel awesome when ending your program in YOU HAVE BEEN TERMINATED.""")
		# ~ time.sleep(3)
		mytext = """Need more convincing? Just join us for our Arnold C workshop and learn how to code completely in
					arnold schwarzenegger one liners and feel awesome when ending your program in YOU HAVE BEEN TERMINATED.
				 """
	else:
		slowprintM("""\n\nUnsure of your coding skills? The Arnold C workshop isn’t the only opportunity to increase your coding
        ability. We will host many other workshops throughout the school year focusing on different coding
        languages or problems so feel free to join the computer science club and increase your coding confidence.""")
		# ~ time.sleep(3)
		mytext = """Unsure of your coding skills? The Arnold C workshop isn’t the only opportunity to increase your coding
					ability. We will host many other workshops throughout the school year focusing on different coding
					languages or problems so feel free to join the computer science club and increase your coding confidence.
				 """

	# ~ 'Convert this Text to Speech in Python'
	# Language we want to use 
	language = 'en'
	myobj = gTTS(text=mytext, lang=language, slow=False) 
	myobj.save("output.mp3") 
	# Play the converted file 
	os.system("start output.mp3")
	if i==2:
		time.sleep(22)


popupmsg("Syntax error missing a semicolon ;")
