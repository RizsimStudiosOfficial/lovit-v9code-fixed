# Incredibox V9CODE PORT TEMPLATE
this was made to make sure you dont have to go thru a hassle lol

# TO CHANGE THE CHECKMARK COLOR
go to css/style.min.css and find the color
its "colV1:" and you can set it to anything like this for example colV1: "#84DCC6" which will change it
but you can set it to anything that fits that versions color

for the other examples check out this: https://github.com/RizsimStudiosOfficial/Incredibox-Latest-Updater/tree/modding

# TO ADD A NEW VERSION
go under the line of 297 and press enter and add this under it for example (change the number to whatever you want like if you want it on v2 change the number to 2) in the script min js file
   ```
   versions.v6 = { // ALIVE
  name: "Alive",
  version: "6",
  date: "2018",
  folder: "asset-v6/",
  looptime: 7111,
  bpm: 135,
  totalframe: 342,
  nbpolo: 7,
  bonusloopA: false,
  bonusendloopA: false,
  colBck: "#110521",
  col0: "#A07DFA",
  col1: "#825FD2",
  col2: "#5F3CA0",
  col3: "#371464",
  col4: "#230A41",
  animearray: [
    {
      name: "1_kick",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "2_snare",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "3_kanye",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "4_tuctuc",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "5_break",
      color: "1e96be",
      uniqsnd: true,
    },
    {
      name: "6_cribasse",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "7_distotut",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "8_screw",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "9_shaolin",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "10_shower",
      color: "825fd2",
      uniqsnd: true,
    },
    {
      name: "11_basse",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "12_hou",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "13_clav",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "14_synth",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "15_yah",
      color: "e11419",
      uniqsnd: true,
    },
    {
      name: "16_hurry",
      color: "f06400",
      uniqsnd: true,
    },
    {
      name: "17_good",
      color: "f06400",
      uniqsnd: true,
    },
    {
      name: "18_mind",
      color: "f06400",
      uniqsnd: true,
    },
    {
      name: "19_haha",
      color: "f06400",
      uniqsnd: true,
    },
    {
      name: "20_wow",
      color: "f06400",
      uniqsnd: true,
    },
  ],
  bonusarray: [
    {
      name: "Alive",
      src: "v6-b1-alive-hb",
      code: "4,6,9,14,18",
      sound: "bonus-alive",
      loop: 3,
    },
    {
      name: "Busta",
      src: "v6-b2-busta-hb",
      code: "1,2,8,11,16",
      sound: "bonus-busta",
      aspire: "aspire-busta",
      loop: 3,
    },
    {
      name: "VR",
      src: "v6-b3-vr-hb",
      code: "3,8,11,12,20",
      sound: "bonus-vr",
      aspire: "aspire-vr",
      loop: 3,
    },
  ],
};
   ```

# FOR VERSION ICON MANAGEMENT
find the sp select thing and go to sp line and find something like this
   ```
          <div class="vicon" id="icon1">
           <div class="img"></div>
           <div class="txt"></div>
           <div class="bul">
            <svg class="icn-svg"><use xlink:href="#ic-check"></use></svg>
               </div>
            </div>
  ```

that is a version icon thingy are whatever for the index and app html thats what you remove if you have extras

# ONLY HAVING ONE VERSION
it should be something like this
```
                <div id="sp-select">
                    <div class="sp-line">
                        <div class="vicon" id="icon1">
                            <div class="img"></div>
                            <div class="txt"></div>
                            <div class="bul">
                                <svg class="icn-svg"><use xlink:href="#ic-check"></use></svg>
                            </div>
                        </div>
                </div>
```

# TO ADD A VERSION
make sure its in the sp select thing or it wont work
``` 
                <div id="sp-select">
                    <div class="sp-line">
                        <div class="vicon" id="icon1">
                            <div class="img"></div>
                            <div class="txt"></div>
                            <div class="bul">
                                <svg class="icn-svg"><use xlink:href="#ic-check"></use></svg>
                            </div>
                        </div>
                        <div class="vicon" id="icon2">
                            <div class="img"></div>
                            <div class="txt"></div>
                            <div class="bul">
                                <svg class="icn-svg"><use xlink:href="#ic-check"></use></svg>
                            </div>
                        </div>
                </div>
```

its a example but just use a text editor like notepad++ or VS Code it will be helpful editing how version you want!

# MAKE YOUR MOD SUPPORTED FOR IOS?
simple find the sndext = "ogg" and vidext = "webm" and change ogg to mp3 and webm to mp4 (BUT IT DOES REQUIRE YOU TO CONVERT STUFF)

# WHAT I RECOMMEND FOR CONVERTING (make mod ios support lol)
for audio i recommend https://online-audio-converter.com/ the reason is because you dont have a limit used it before and it was great!

for video i recommend https://www.freeconvert.com/webm-to-mp4

