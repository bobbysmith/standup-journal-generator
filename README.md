Just a script to create a monthly formatted txt file for me to take notes for standup/what I did each day. If you like it you can use it but you'll probably want to change the out file path to what works for you :)

If you want to make this a CLI command:
#### 1. Open a terminal and go to the directory containing the script and run:
`chmod +x standup.py`

#### 2. Move the script to a directory that's included in your system's PATH. I put it in `/usr/local/bin`.
`sudo mv standup.py /usr/local/bin/standup`

#### 3. Run command in the console
`standup`

Output looks like this but for the whole month of weekdays.

```
MON 2023-10-02
============================
- this is an example of how i use it
============================

TUE 2023-10-03
============================
============================

WED 2023-10-04
============================
============================

THU 2023-10-05
============================
============================

FRI 2023-10-06
============================
============================
```
