## 1 ##
📂 text_tooltip 📂

CZ Aplikace text_tooltip je jednoduchý a užitečný nástroj pro zobrazování zkopírovaného textu jako tooltipu přímo u kurzoru. Tento projekt vznikl pro potřeby kontroly různých dat, kdy kopírujeme text a potřebujeme jej porovnat.. <br><br>
EN The text_tooltip app is a simple and handy tool that displays copied text as a tooltip right next to the cursor. This project was created for the needs of checking different data when we copy text and need to compare it..

### Funkce ###
V první řadě musíte vytvořit .exe soubor. 
Je to jednoduché. Použitjete VS code a konzoli (View -> Terminal) a zadaáte tyto příkazy:
je potřeba být ve složce, ve které se nachází python soubor text_tooltip_1.1.py:
cd C:\Users\jpawlas\Desktop\tooltip_project
pip install pyinstaller
pyinstaller --onefile text_tooltip_1.1.py #### Tento příkaz vytvoří kompletní program. #### 

Po spuštění program otevře okno, ve kterém uvidíte probíhající děje. 
Pokud použijeme klávesovou zkratku ctrl+c, text se zkopíruje také do paměti programu.
Prostřednictvím zkratky ctrl+shift+q zobrazíme zkopírovaný text vedle kurzoru myši. 
Text v rámečku zmizí po 5000 milisekundách.
Samozřejmě program si můžete v .py souboru upravovat. 
V konzoli VS code můžete následně vytvořit celý nový .exe program pomocí příkazu: pyinstaller **--onefile text_tooltip_1.1.py**
ten bude reagovat na vaše úpravy. 

### Features ###
First of all, you need to create an .exe file.
It's simple. You use VS code and the console (View -> Terminal) and enter these commands:
You need to be in the folder where the python file text_tooltip_1.1.py is located:
cd C:\Users\jpawlas\Desktop\tooltip_project
pip install pyinstaller
pyinstaller --onefile text_tooltip_1.1.py #### This command will create a complete program. ####

After running the program, a window will open in which you can see the current events.
If we use the keyboard shortcut ctrl+c, the text will also be copied to the program memory.
Using the shortcut ctrl+shift+q, we will display the copied text next to the mouse cursor.
The text in the frame will disappear after 5000 milliseconds.
Of course, you can edit the program in the .py file.
In the VS code console, you can then create a whole new .exe program using the command: pyinstaller **--onefile text_tooltip_1.1.py**
which will respond to your edits.
