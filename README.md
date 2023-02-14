Geekcomputers: <q><i>Here is some more detailed information about the scripts I have written.  I do not consider myself a programmer, I create these little programs as experiments to have a play with the language, or to solve a problem for myself.  I would gladly accept pointers from others to improve the code and make it more efficient, or simplify the code.  If you would like to make any comments then please feel free to email me at craig@geekcomputers.co.uk.</i></q>

In the scripts the comments etc are lined up correctly when they are viewed in SciTE Editor.  This is what I use to code AutoIt scripts.

<ol>
  <li>
    <a href="https://github.com/JeanPaulLucien/AutoIt/blob/master/clipboard_logger.au3">clipboard_logger.au3</a>
    <ul>
      <li>was written by Rob Fuller (a.k.a Mubix from Room362.com) on the Hak5 podcast. This is like a keyboard logger but for the clipboard. Anything that is copied to the clipboard will be tracked into a logfile. I have tried this with some password managers as well and it still captures the password.</li>
    </ul>
  </li>
  <li><a href="#">environment.au3</a>
    <ul>
      <li>This is what I run when I get a new PC, so I will have all the registry keys and folders I need for my workflow.</li>
    </ul>
  </li>
  <li><a href="#">evernote_details.au3</a>
    <ul>
      <li>This is a simple exe that will get the location of your evernote database and then work out the size of it.  I wrote this as someone was nw to evernote and wanted to know where it is stored and how big the database is, so he can keep track as he adds documents to evernote.</li>
    </ul>
  </li>

free_diskspace.au3 - This will show you the free space on all your fixed and network drives, very simple.

get_putty_sessions.au3 - This script will get all your PuTTY sessions stored in the registry and output them to a text file.  This to me is handy, if I need to make changes to any of the session config, I always use this to get a full list, so I can tick off the servers once I have made the change.

logoff.au3 - This is a simple wrapper script/splash screen around a logoff batch file I have.  The only reason I wrote this was because I have a new microsoft keyboard and I have assigned the logoff batch file to a hotkey.  I wrote this so if anyone decides to see what the hotkeys do then they will see this so my machine won't shutdown straight away.

security_eventlog.au3 - This interrogates the security part of the Event log, it searches for failed login attempts. It displays the last failed login attempt on the screen.  It also copies all security details into a logfile.  It then does a backup of the event log then clears it out.
  </ol>
