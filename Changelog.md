# Changelog

**2.0.0** - [2025.07.26] Over a year later, on a hot July day
<br/>

    VERSION 2 (yay)

    It's been a while but there are some big changes, thank you all so much for the support in
    getting here!


    - First:
    The library now has over 700 IRs and is over 2 GB in size. I'm always working on trying to 
    improve my methods of collecting and editing, so I hope that the quality of the IRs in the
    library continues to improve too. Included are some made from a signal generator I've since
    created called homados, which is free and open source.


    - Next:
    There's a new References page! This is for a consistent and clear way to check information
    about equipment used in Impulse Responses as the library transitions to generic, descriptive
    names. Many IRs have been renamed (!). This transition is in hopes to prevent any confusion
    about affiliation with brands and trademarks -- the goal is to make it clear that *nothing* in 
    this library is endorsed or made by (or affiliated with!) any entities whose names could be 
    associated with that equipment or process, unless they specifically request so. Any authorized 
    representation can be confirmed by checking the "Contributors" section in the README. That page
    will have more info about that. Expect the language in it to evolve over time to be more precise
    and well-formatted, but I think it's a helpful start.


    - The good stuff:
    The categories have also been generalized a bit more and this update has added
    so many new kinds of things that were previously lacking in quality or selection. I am
    especially proud of all the weird objects. More will come. I am also going to try out using
    the github releases feature to make this library easier to download for beginners.


    - The good (but breaking changes) stuff:
    SDIR and presets are going away. True Stereo in Space Designer was really the only thing 
    keeping SDIR around, and as the library grows I'd prefer not to keep duplicates when there are 
    good, easy, and accessible options for loading / converting these to work otherwise. Similarly
    for presets, they're just too inconsistent and labor intensive when there are so many formats 
    to keep up with. If someone decides they want to make Presets for these and share them be my 
    guest but I won't be adding those to this repo or making any new ones. Additionally, many 
    categories have been refreshed with new names which will mean there are some backwards 
    compatibility issues. Hopefully most of these are a one-time, low effort fix, the goal is to
    have this happen less over time as categories become more precise. As a result of this, the 
    preexisting portion of the library now takes up less disk space and more IRs can now be added 
    in the same storage footprint.


    - What's next: I'd like to start getting more rooms again. Rooms tend to be the bread and
    butter of a lot of other libraries so it's not like there is a huge need from me, but I think 
    this library now has a relatively quite small selection and a lot of opportunity to grow.
    Outdoor spaces are another area I think are lacking a bit. I've slowly been acquiring a much
    better setup for location recording recently too, and I'd like to use it to grab a bunch more
    automotive and other difficult responses. As always, me know what you'd like to see!


    Okay. Thank you for reading all that (or not). Here's the finer details:


    + README: Overall minor changes to text layout and spacing
    + README: Fixed up some language around the library size for clarity.
    + README: Added References page to the bottom links section.
    + README: Removed all social links, added kofi donation link.
    + References: Inclusion of statement regarding trademark use, list of identifiers for
      equipment with abstracted names on Impulse Response files, and additional information.
    - All SDIR files and presets, and their specific folders.
    
    Added the following categories and subcategories:
     + Enclosed Spaces/Automobiles
     + Enclosed Spaces/Miscellaneous
     + Instruments/Ukuleles
     + Noise
     + Noise/Noise Colors
     + Noise/White Noise Fades
     + Objects/Containers
     + Objects/Containers/Historical
     + Objects/Containers/Metal Bowls
     + Objects/Containers/Miscellaneous
     + Objects/Containers/Nitro Cold Brew Keg
     + Objects/Containers/Soda Can
     + Objects/Containers/Storage Bins
     + Objects/Glass
     + Objects/Metallic/Car Brake Rotor
     + Objects/Metallic/Frames
     + Objects/Metallic/Lamp Reflectors
     + Objects/Metallic/Tanks
     + Objects/Plastics
     + Objects/Plastics/Light Switch
     + Objects/Vinyl
     + Outdoors/Public/Forests
     + Outdoors/Public/Streets
     + Phenomena
     + Phenomena/Rain
     + Rooms/Commercial/Hotels/Guest Rooms
     + Rooms/Commercial/Shops/Gold Coffee Shop
     + Rooms/Historical/Landmarks
     + Rooms/Historical/Religious
     + Rooms/Historical/Shelters
     + Rooms/Public/Arenas
     + Rooms/Public/Colleges & Universities
     + Rooms/Public/Colleges & Universities/Missouri State University
     + Rooms/Public/Convention Centers
     + Rooms/Public/Convention Centers/Fort Worth Convention Center
     + Rooms/Public/Convention Centers/Phoenix Convention Center
     + Rooms/Public/Miscellaneous Public
     + Speakers/Amplifiers
     + Speakers/Amplifiers/Practice Amps
     + Speakers/Computers
     + Speakers/Monitors
     + Speakers/Subwoofers
     + Springs/Letter Holding Coil
     + Springs/Space Heater Spring Tank
     + Springs/Spring Tube Toys
     + Synthesized/Chaos
     + Synthesized/Chromatic/Scale Sine Decays
     + Synthesized/Rooms
     + Synthesized/Rooms/Silly Spaces
     + Synthesized/Rooms/Synth Room Generator 1
     + Synthesized/Signaling
     + Synthesized/Signaling/DTMF Tones

    Updated the following categories and subcategories:
     + Enclosed Spaces/2002 Sedan -> Enclosed Spaces/Automobiles/2002 Sedan
     + Hardware/2000s Digital Piano -> Hardware/2004 Digital Piano
     + Hardware/Rackmount/Magical 2830 Interface -> Hardware/Rackmount/Rackmount USB Interface 1
     + Hardware/Rackmount/SSM-1750 -> Hardware/Rackmount/Stereo Mixer 1
     + Objects/Basilica Dome Glass Bowls -> Objects/Glass/Basilica Dome Glass Bowls
     + Objects/Talkbox -> Hardware/Talkbox
     + Outdoors/Commercial/Universities -> Outdoors/Public/Colleges & Universities
     + Plates/Conner Plate I/"Plate I" * -> Plates/Conner Plate I/"Conner Plate I" *
     + Rooms/Commercial/Firenze Parking Garage -> Rooms/Commercial/Parking Garages
     + Rooms/Historical/Drumheller's Little Church -> Rooms/Historical/Religious/Drumheller's Little Church
     + Rooms/Historical/Menorcan Spanish Civil War Bunkers -> Rooms/Historical/Shelters/Menorcan Spanish Civil War Bunkers
     + Rooms/Historical/Sunnybrook Farm Willowdale Church -> Rooms/Historical/Religious/Sunnybrook Farm Willowdale Church
     + Rooms/Historical/The Pantheon (Rome) -> Rooms/Historical/Landmarks/The Pantheon (Rome)
     + Rooms/Public/Orange County Convention Center -> Rooms/Public/Convention Centers/Orange County Convention Center
     + Rooms/Public/University of Central Florida -> Rooms/Public/Colleges & Universities/University of Central Florida
     + Rooms/Residential/Unknown Houses -> Rooms/Residential/Miscellaneous Residential
     + Speakers/4x14 Garage PA Sub -> Speakers/Subwoofers/4x14 Garage PA Sub
     + Speakers/Laptop MBA -> Speakers/Computers/Laptops
     + Speakers/Telephones -> Speakers/Phones
     + Speakers/Tiny T-Shirt Amplifier -> Speakers/Amplifiers/Tiny T-Shirt Amplifier
     + Speakers/Tiny Keyboard Speaker -> Speakers/Toys and Novelty
     + Springs/Ronald Jazz Chorus 120 -> Speakers/Amplifiers/Jazz Chorus 120

    Added the following impulse responses:
    Enclosed Spaces
     + Storm Drain Bang Snap
    Instruments
     + Concert Ukulele Close Mono
     + Concert Ukulele Close Stereo (Tail Only)
     + Concert Ukulele Close Stereo
     + Concert Ukulele Contact Mic
     + Soprano Ukulele Close Mono
     + Soprano Ukulele Close Stereo (Tail Only)
     + Soprano Ukulele Close Stereo
     + Soprano Ukulele Contact Mic
    Noise
     + Blue Noise 0.0005s (500us)
     + Blue Noise 0.0010s (1ms)
     + Blue Noise 0.0050s (5ms)
     + Blue Noise 0.0100s (10ms)
     + Blue Noise 0.0500s (50ms)
     + Blue Noise 0.1000s (100ms)
     + Blue Noise 0.5000s (500ms)
     + Blue Noise 1s
     + Blue Noise 5s
     + Blue Noise 10s
     + Blue Noise 50s
     + Brown Noise 0.0005s (500us)
     + Brown Noise 0.0010s (1ms)
     + Brown Noise 0.0050s (5ms)
     + Brown Noise 0.0100s (10ms)
     + Brown Noise 0.0500s (50ms)
     + Brown Noise 0.1000s (100ms)
     + Brown Noise 0.5000s (500ms)
     + Brown Noise 1s
     + Brown Noise 5s
     + Brown Noise 10s
     + Brown Noise 50s
     + Pink Noise 0.0005s (500us)
     + Pink Noise 0.0010s (1ms)
     + Pink Noise 0.0050s (5ms)
     + Pink Noise 0.0100s (10ms)
     + Pink Noise 0.0500s (50ms)
     + Pink Noise 0.1000s (100ms)
     + Pink Noise 0.5000s (500ms)
     + Pink Noise 1s
     + Pink Noise 5s
     + Pink Noise 10s
     + Pink Noise 50s
     + Violet Noise 0.0005s (500us)
     + Violet Noise 0.0010s (1ms)
     + Violet Noise 0.0050s (5ms)
     + Violet Noise 0.0100s (10ms)
     + Violet Noise 0.0500s (50ms)
     + Violet Noise 0.1000s (100ms)
     + Violet Noise 0.5000s (500ms)
     + Violet Noise 1s
     + Violet Noise 5s
     + Violet Noise 10s
     + Violet Noise 50s
     + White Noise 0.0005s (500us)
     + White Noise 0.0010s (1ms)
     + White Noise 0.0050s (5ms)
     + White Noise 0.0100s (10ms)
     + White Noise 0.0500s (50ms)
     + White Noise 0.1000s (100ms)
     + White Noise 0.5000s (500ms)
     + White Noise 1s
     + White Noise 5s
     + White Noise 10s
     + White Noise 50s
     + White Noise Equal Power In 0.100s (100ms)
     + White Noise Equal Power In 0.500s (500ms)
     + White Noise Equal Power In 1s
     + White Noise Equal Power In 5s
     + White Noise Equal Power In 10s
     + White Noise Equal Power Out 0.100s (100ms)
     + White Noise Equal Power Out 0.500s (500ms)
     + White Noise Equal Power Out 1s
     + White Noise Equal Power Out 5s
     + White Noise Equal Power Out 10s
     + White Noise Exp Decay 0.100s (100ms)
     + White Noise Exp Decay 0.500s (500ms)
     + White Noise Exp Decay 1s
     + White Noise Exp Decay 5s
     + White Noise Exp Decay 10s
     + White Noise Linear Decay 0.100s (100ms)
     + White Noise Linear Decay 0.500s (500ms)
     + White Noise Linear Decay 1s
     + White Noise Linear Decay 5s
     + White Noise Linear Decay 10s
     + White Noise Log Decay 0.100s (100ms)
     + White Noise Log Decay 0.500s (500ms)
     + White Noise Log Decay 1s
     + White Noise Log Decay 5s
     + White Noise Log Decay 10s
     + White Noise S-Curve In 0.100s (100ms)
     + White Noise S-Curve In 0.500s (500ms)
     + White Noise S-Curve In 1s
     + White Noise S-Curve In 5s
     + White Noise S-Curve In 10s
     + White Noise S-Curve Out 0.100s (100ms)
     + White Noise S-Curve Out 0.500s (500ms)
     + White Noise S-Curve Out 1s
     + White Noise S-Curve Out 5s
     + White Noise S-Curve Out 10s
    Objects
     + Ostia Antica Small Dolia Clap
     + Ostia Antica Stacked Dolia Claps
     + Small Metal Dog Bowl Mono
     + Small Metal Dog Bowl Stereo
     + Snack Chip Cylinder Small
     + Nitro Cold Brew Keg Combined
     + Nitro Cold Brew Keg Inside
     + Nitro Cold Brew Keg Surface 1
     + Nitro Cold Brew Keg Surface 2
     + Soda Can (7.5 fl oz) Contact
     + Soda Can (7.5 fl oz)
     + Soda Can (12 fl oz) Contact Mic
     + Soda Can (12 fl oz)
     + Soda Can Pressure Release
     + Soda Fizz Wide
     + 45L Plastic Storage Bin
     + Car Brake Rotor
     + Scrap Extruded Aluminum LED Fixture Frame Contact Mic
     + Aluminum Lamp Reflector 8.5 inch (No Clamp) Contact Mic
     + Aluminum Lamp Reflector 8.5 inch (No Clamp) Mono
     + Aluminum Lamp Reflector 8.5 inch (No Clamp) Stereo
     + Damped Propane Tank Knuckle
     + Light Switch Flick 1
     + Light Switch Flick 2
     + Light Switch Flick 3
     + Light Switch Flick 4
     + Light Switch Flick 5
     + Exercise Ball Boundary Mic
     + Exercise Ball Contact Mic
    Outdoors
     + Small Forest Clearing 1 Balloon
     + Small Forest Clearing 2 Bang Snap
     + Medium Gazebo Bang Snap
     + PCC 3rd Street Corridor XY Balloon Heavy Denoise (Tail Only) 
     + PCC 3rd Street Corridor XY Balloon Heavy Denoise
     + PCC North 300 Level North Terrace Combined Balloon
     + PCC North 300 Level North Terrace Shotgun Mic Balloon
     + PCC North 300 Level North Terrace XY Balloon
     + Suburb Street Distant Bang Snap
    Phenomena
     + Close Umbrella Raindrops Dense Fade
     + Close Umbrella Raindrops Sparse Fade
     + Close Umbrella Reversed Raindrops Dense Fade
     + Close Umbrella Reversed Raindrops Sparse Fade
     + Skylight Rain Wide
     + Sloshing Drains Flattened
     + Sloshing Drains
    Rooms
     + Orlando Ballroom PA Mono (Tail Only)
     + Orlando Ballroom PA Mono
     + Hotel Room 1 XY (Balloon)
     + Gold Coffee Shop Bathroom (Closed)
     + Gold Coffee Shop Bathroom (Open)
     + Gold Coffee Shop Lobby Corner
     + Gold Coffee Shop Quiet Room Diffuse 
     + Giant Center Temporary Flown PA Matted Rink Seats (High Gain)
     + Giant Center Temporary Flown PA Matted Rink Seats (Low Gain)
     + Giant Center Temporary Flown PA Upper Bleachers (High Gain)
     + Giant Center Temporary Flown PA Upper Bleachers (Low Gain)
     + MSU Arena Court Seating (Heavy Denoise)
     + MSU Arena Lower Bleachers Rear (Heavy Denoise)
     + MSU Arena Upper Bleachers Rear (Heavy Denoise)
     + MSU Arena Upper Bleachers Side (Heavy Denoise)
     + FWCC Arena Balloon (Tail Only)
     + FWCC Arena Balloon
     + PCC North 300 Level Exhibit Hall Combined Balloon Far
     + PCC North 300 Level Exhibit Hall Shotgun Mic Balloon Far
     + PCC North 300 Level Exhibit Hall XY Balloon Far
     + PCC North 300 Level Prefunction Hall Combined Balloon Far
     + PCC North 300 Level Prefunction Hall Shotgun Mic Balloon Far
     + PCC North 300 Level Prefunction Hall XY Balloon Far
     + Weston's Backrooms Hall Mono Snap
     + Engineering II Atrium Stereo Clap
     + College House Bedroom Stereo 1
     + College House Bedroom Stereo 2
     + Paul's Place Mono Clap
     + Tile Dormitory Clap
    Speakers
     + Practice Bass Amp 1 -30dB
     + Practice Bass Amp 1 -60dB
     + Practice Bass Amp 2 -30dB
     + Practice Bass Amp 2 -60dB
     + 12in 2-Way Wedge Floor Monitor
    Springs
     + Letter Holding Coil Contact Mic Mono
     + Letter Holding Coil Contact Mic Stereo (Tail Only)
     + Letter Holding Coil Contact Mic Stereo
     + Letter Holding Coil Mono
     + Letter Holding Coil Stereo (Tail Only)
     + Letter Holding Coil Stereo
     + Space Heater Spring Tank Contact Mic
     + Space Heater Spring Tank Mono
     + Space Heater Spring Tank Stereo
     + Spring Tube Toy 39in Sweep Smooth 
     + Spring Tube Toy 24in Shake 
     + Spring Tube Toy 24in Strike 
     + Spring Tube Toy 24in Sweep Sharp 
     + Spring Tube Toy 24in Sweep Smooth 
     + Spring Tube Toy 39in Pluck Hard 
     + Spring Tube Toy 39in Pluck Soft 
     + Spring Tube Toy 39in Shake 
     + Spring Tube Toy 39in Strike 
     + Spring Tube Toy 39in Sweep Opening 
     + Spring Tube Toy 39in Sweep Sharp
    Synthesized
     + Sparse Chaotic Impulses 1s
     + Sparse Chaotic Impulses 2s
     + Sparse Chaotic Impulses 4s
     + Sparse Chaotic Impulses 10s
     + Full MIDI Range Chromatic Sine Decay
     + Full MIDI Range Major Scale Sine Decay
     + Full MIDI Range Minor Scale Sine Decay
     + Full MIDI Range Wholetone Sine Decay 1
     + Full MIDI Range Wholetone Sine Decay 2
     + Single Octave Chord Augumented Sine Decay
     + Single Octave Chord Diminished Sine Decay
     + Single Octave Chord Dominant 7 Sine Decay
     + Single Octave Chord Half Diminished Sine Decay
     + Single Octave Chord Major 6 Sine Decay
     + Single Octave Chord Major 6 9 Sine Decay
     + Single Octave Chord Major 7 Sine Decay
     + Single Octave Chord Major Add9 Sine Decay
     + Single Octave Chord Major Sine Decay
     + Single Octave Chord Minor 6 Sine Decay
     + Single Octave Chord Minor 6 9 Sine Decay
     + Single Octave Chord Minor 7 Sine Decay
     + Single Octave Chord Minor Major 7 Sine Decay
     + Single Octave Chord Minor Sine Decay
     + Single Octave Chord Sus2 Sine Decay
     + Single Octave Chord Sus4 Sine Decay
     + Single Octave Mode Aeolian (Minor Scale) Sine Decay
     + Single Octave Mode Dorian Sine Decay
     + Single Octave Mode Ionian (Major Scale) Sine Decay
     + Single Octave Mode Locrian Sine Decay
     + Single Octave Mode Lydian Sine Decay
     + Single Octave Mode Mixolydian Sine Decay
     + Single Octave Mode Phyrgian Sine Decay
     + A Major 9 Wide Saw
     + F# Minor 11 Wide Saw
     + Silly Space 1
     + Silly Space 2
     + Silly Space 3
     + Silly Space 4
     + Synth Room Gen 1 Size 1 (Tail Only)
     + Synth Room Gen 1 Size 1 (With Direct)
     + Synth Room Gen 1 Size 2 (Tail Only)
     + Synth Room Gen 1 Size 2 (With Direct)
     + Synth Room Gen 1 Size 3 (Tail Only)
     + Synth Room Gen 1 Size 3 (With Direct)
     + Synth Room Gen 1 Size 4 (Tail Only)
     + Synth Room Gen 1 Size 4 (With Direct)
     + Synth Room Gen 1 Size 5 (Tail Only)
     + Synth Room Gen 1 Size 5 (With Direct)
     + DTMF Full Table
     + DTMF No ABCD
     + DTMF Only Columns
     + DTMF Only Rows
    Utility
     + Zero Sample Length
    
    Updated the following impulse responses:
    Enclosed Spaces
     + "2002 Sedan" * -> "2002 Sedan Speakers" *
    Hardware
     + "2000s Digital Piano" * -> "2004 Digital Piano" *
     + "Magical 2830 Interface" * -> "Rackmount USB Interface 1" *
     + "SSM-1750" * -> "Stereo Mixer 1" *
    Rooms
     + (Arroyo House) "" * -> "Arroyo House" *
     + "College" * -> "College House" *
     + (College) "Garage" * -> "College House Garage" *
     + (Ranch House) "" * -> "Ranch House" *
    Speakers
     + "JC-120" * -> "JC-120 Spring" *
     + JC-120 True Stereo Chorus no Reverb -> JC-120 True Stereo Chorus Dry
     + JC-120 True Stereo Chorus with Reverb -> JC-120 True Stereo Chorus Spring
     + "Laptop MBA" * -> "Laptop 2011 Light" *
     + Smartphone 1 Speaker Dispersion -> Smartphone 2020 Speaker Dispersion

**1.3.0** - [2024.01.15] A cool and overcast January evening (a long time later...)
<br/>

    A whole overhaul of some categories and titles, and a bunch of new IRs!!! Yayyyyyyy!!!!!!

    It's been almost a year... Sorry about that. I've still been making quite a few IRs, but
    I've been through a whole new computer after the previous catastrophically failed, some traveling,
    a load of schoolwork, and some other assorted events.

    Good news though, there's a lot of new IRs that have been building up (Over 100!). In particular, I've
    been recording a bunch more objects and instruments. As a result I'm not too satisfied with the existing
    folder hierarchy and a bunch of renaming and grouping has happened. See below.

    There's also some more gear and rooms and spaces, some of these took a while because I wasn't very happy
    with the post work on them. I've revisited and polished to be okay with including, though that means some
    authenticity as a result has been lost. And some are a little weird.

    Anyway, I'm really happy to share a bunch of new stuff and have even more things planned upcoming.
    Thank you all for being patient, enough blabber.

    Added the following categories and subcategories:
     + Enclosed Spaces/Watercraft
     + Hardware/Rackmount
     + Hardware/Rackmount/Magical 2830 Interface
     + Hardware/Tape
     + Hardware/Tape/Consumer Cassette Deck
     + Hardware/Tape/Portable Cassette Recorder
     + Hardware/Tape/Sticky Quarter Inch 4 Track R2R
     + Instruments/Autoharp
     + Instruments/Cymbals
     + Objects/Metallic
     + Objects/Natural
     + Objects/Pipes and Tubes
     + Objects/Swords
     + Outdoors/Public/Parks
     + Rooms/Commercial/Shops
     + Rooms/Commercial/Shops/Ancient Wand Shop
     + Rooms/Public
     + Rooms/Public/Orange County Convention Center
     + Rooms/Public/University of Central Florida
     + Speakers/Miscellaneous
     + Springs/Boom Arm Spring
     + Synthesized/Granular
     + Synthesized/Unit Impulse Pitch Remap

    Updated the following categories and subcategories:
     + Esoteric Hardware -> Hardware
     + Formant and Resonant -> Objects
     + Strings -> Instruments
     + Esoteric Hardware/RadicalShack SSM-1750 -> Hardware/Rackmount/SSM-1750
     + Esoteric Hardware/Railings -> Objects/Metallic/Rails
     + Esoteric Hardware/Rusty Steel Sheet -> Objects/Metallic/Sheets
     + Esoteric Hardware/Tiny T-Shirt Amplifier -> Speakers/Tiny T-Shirt Amplifier
     - Esoteric Hardware/Wire Rack Shelf
       -> Objects/Metallic/Rails
     + Formant and Resonant/Breathy Vowels -> Instruments/Breathy Vowels
     + Formant and Resonant/Instrumental Resonance -> Instruments/Miscellaneous
                                                   -> Instruments/Raw Piezo Captures
                                                   -> Instruments/Wind Section Bursts
     + Formant and Resonant/Toilet -> Objects/Toilets
     + Rooms/Craft Coffee Shop -> Rooms/Shops/Craft Coffee Shop
     + Rooms/Tall Coffee Shop -> Rooms/Shops/Tall Coffee Shop
     + Strings/Winter Upright -> Instruments/Winter Upright Piano

    Added the following impulse responses:
    Enclosed Spaces
     + Catamaran Hull
    Hardware
     + Consumer Cassette Deck Click
     + Consumer Cassette Deck Sweep
     + Magical 2830 Interface Passive Reamp DI Loopback
     + Magical 2830 Interface RCA Loopback
     + Portable Cassette Recorder Click Mic In Line Out
     + Portable Cassette Recorder Click Mic In Speaker Out
     + Portable Cassette Recorder Sweep Direct In Line Out
     + Portable Cassette Recorder Sweep Mic In Speaker Out
     + Sticky Quarter Inch 4 Track R2R Click Mono Low Gain
     + Sticky Quarter Inch 4 Track R2R Click Stereo High Gain
     + Sticky Quarter Inch 4 Track R2R Click Stereo Low Gain
     + Sticky Quarter Inch 4 Track R2R Sweep Stereo
    Instruments
     + Antique Keyboard Glockenspiel
     + Autoharp A7
     + Autoharp Am
     + Autoharp Bb
     + Autoharp C
     + Autoharp C7
     + Autoharp Chromatic
     + Autoharp D
     + Autoharp D7
     + Autoharp Damped
     + Autoharp Dm
     + Autoharp E7
     + Autoharp Eb
     + Autoharp F
     + Autoharp F7
     + Autoharp G
     + Autoharp G7
     + Autoharp Gm
     + Bent Mouthpiece Tube
     + China Cymbal Contact Damped
     + China Cymbal Contact Resonant
     + China Cymbal Sweep SDC 1
     + China Cymbal Sweep SDC 2
     + Dramyin
     + Glockenspiel Sweep 1
     + Glockenspiel Sweep 2
     + Lap Harp 1
     + Lap Harp 2
     + Marx Violin-Uke
     + Pink Grand Toy Piano
     + Rawap
     + Steel Pan Medium Sweep 1
     + Steel Pan Medium Sweep 2
     + Steel Pan Small Sweep 1
     + Steel Pan Small Sweep 2
     + Toy Erhu
     + Toy Ukulele Character
     + Toy Ukulele Cheap
     + Toy Ukulele VERY Cheap
     + Violin Sweep
    Objects
     + Basilica Dome Glass Bowls Big Contact Weird
     + Basilica Dome Glass Bowls Little Contact Weird
     + Basilica Dome Glass Bowls Nested Contact Weird
     + Broadsword Mid Contact
     + Broadsword Tip Contact 1
     + Broadsword Tip Contact 2
     + Cinder Block Contact Inner
     + Cinder Block Contact Outer
     + Conch Click
     + Conch Contact Sweep
     + Conch XY Sweep
     + Corrugated Blowing Pipe 1
     + Corrugated Blowing Pipe 2
     + Corrugated Pipe 1
     + Corrugated Pipe 2
     + Corrugated Pipe 3
     + Cruise Ship Cabin HVAC Ceiling Plate
     + Dinosaur Bone 1
     + Papaya Tree Inner Trunk Impact
     + Papaya Tree Outer Trunk Impact
     + Toy Corrugated Pipe 1 Compressed
     + Toy Corrugated Pipe 1 Expanded
     + Toy Corrugated Pipe 2 Compressed
     + Toy Corrugated Pipe 2 Expanded
    Outdoors
     + Florida SR40 Bridge Underpass
     + Old Home Backyard Click Weird
     + Rockefeller Gardens Field Stage
    Rooms
     + Ancient Wand Shop
     + MSB Brick Stairwell Downstairs
     + MSB Brick Stairwell Upstairs
     + Old Audio Engineering Club Room
     + Old Home Fireplace
     + OCCC Freight Elevator
     + OCCC Theater Storage Barrier
    Speakers
     + Contact Mic on Contact Transducer
    Springs
     + Boom Arm Spring Flick Band Pass
     + Boom Arm Spring Flick High Pass
     + Boom Arm Spring Flick
    Synthesized
     + Funny Modulated Delay Room
     + Resonant Warbled Noise Decay 1
     + Resonant Warbled Noise Decay 2
     + Resonant Warbled Noise Decay 3
     + Granular Room 1 Click 1
     + Granular Room 1 Click 2
     + Granular Room 1 Click 3
     + Granular Room 1 Sweep 1s
     + Granular Room 1 Sweep 5s
     + Granular Room 1 Sweep 10s
     + Granular Room 1 Sweep 50s
     + Granular Room 2 Click 1
     + Granular Room 2 Click 2
     + Granular Room 2 Click 3
     + Granular Room 2 Sweep 1s
     + Granular Room 2 Sweep 5s
     + Granular Room 2 Sweep 10s
     + Granular Room 2 Sweep 50s
     + Unit Impulse Pitch Remap A
     + Unit Impulse Pitch Remap A#
     + Unit Impulse Pitch Remap B
     + Unit Impulse Pitch Remap C
     + Unit Impulse Pitch Remap C#
     + Unit Impulse Pitch Remap D
     + Unit Impulse Pitch Remap D#
     + Unit Impulse Pitch Remap E
     + Unit Impulse Pitch Remap F
     + Unit Impulse Pitch Remap F#
     + Unit Impulse Pitch Remap G
     + Unit Impulse Pitch Remap G#
     + Unit Impulse Pitch Remap SMASHED Chromatic

**1.2.3** - [2023.04.25] A rainy and decently hot April Tuesday
<br/>

    A bunch of new categories, sounds, and some updated names!

    Starting off with the latter, to prevent potential future conflicts regarding names:
    I've renamed a few directories and IRs to reflect a more generic title. The samples themselves
    remain unchanged, but these names are incompatible with previous versions. Sorry!

    Ok now for the fun stuff, it's not a massive collection this time around but I've got some
    weird gear and cool rooms added in, and some really basic color-bass inspired chromatic bits.

    Added the following categories and subcategories:
     + Esoteric Hardware/2000s Digital Piano
     + Esoteric Hardware/Tiny T-Shirt Amplifier
     + Rooms/Commercial/Hotels/Ballrooms
     + Rooms/Commercial/Hotels/Bathrooms
     + Synthesized/Chromatic
     + Synthesized/Chromatic/Stacked Synth Chords

    Added the following impulse responses:
    Esoteric Hardware
     + 2000s Digital Piano Mic Loopback Impulse Echo
     + 2000s Digital Piano Mic Loopback Impulse
     + 2000s Digital Piano Tone Click Dry
     + 2000s Digital Piano Tone Click Reverb Hall 1
     + 2000s Digital Piano Tone Click Reverb Hall 2
     + 2000s Digital Piano Tone Click Reverb Room 1
     + 2000s Digital Piano Tone Click Reverb Room 2
     + Tiny T-Shirt Amplifier Line Out 
     + Tiny T-Shirt Amplifier Tone 0
     + Tiny T-Shirt Amplifier Tone 1
     + Tiny T-Shirt Amplifier Tone 2
     + Tiny T-Shirt Amplifier Tone 3
     + Tiny T-Shirt Amplifier Tone 4
     + Tiny T-Shirt Amplifier Tone 5
     + Tiny T-Shirt Amplifier Tone 6
     + Tiny T-Shirt Amplifier Tone 7
     + Tiny T-Shirt Amplifier Tone 8
     + Tiny T-Shirt Amplifier Tone 9
     + Tiny T-Shirt Amplifier Tone 10
    Rooms
     + College Master Bedroom Light Treatment
     + Palm Ballroom
     + Royal Ballroom
    Synthesized
     + C Giga Lydian #15 Supersquare
     + C Lydian 17 #15 Supersaw
     + C Major 13 Supersaw
     + E Minor 11 Supersaw
     + G Major 9 Supersaw

**1.2.2** - [2023.01.11] A sunny and cool January Wednesday
<br/>

    A variety of new household and other impulses!

    The largest and most noticeable set from this batch will be the SSM-1750 ones, I've included
    both SDIR and WAV for all of these because they are True Stereo. I've grabbed responses for
    different channel configurations as well as a relatively thorough sweep of settings from the
    unit's delay. I already made 3 IRs previously from this unit which were not recorded True
    Stereo, so no SDIR for them. The Balance Right Full IR is a mirror edited version of the Left
    counterpart, as I mistakenly did not record that one TS in the original session. It should be
    essentially exactly the same as what one would expect anyway, but in case that is important
    info to someone there you have it. These have very light noise reduction so in some of them
    one may hear aliasing artifacts.

    I also grabbed (another!) sustain pedal IR of the Winter Upright, knowing this time I could
    get a nicer clean one having been a little more prepared with adequate gear on hand. I decided
    to call this new one "Hyper Sustain" because the tuning has since changed a little again (thanks
    to the weather). It should still be relatively in tune and have quite a clean and long tail.

    The first time I attempted to record the toilet bowl IR I ultimately dropped my field recorder
    in the toilet. Fortunately it survived with no harm, however, the resulting responses were not
    very good. So it endured another scary round of recording, safely and more securely. The new
    IR was good, and I will likely not be creating more of this type soon.

    Added the following subcategories:
     + Enclosed Spaces/Old Home Appliances
     + Esoteric Hardware/Old Cabinet Gramophone
     + Formant and Resonant/Toilet
     + Rooms/Residential/Old Home
    
    Added the following impulse responses:
    Enclosed Spaces
     + Old Home Dryer
     + Old Home Oven
     + Old Home Washing Machine
    Esoteric Hardware
     + Old Cabinet Gramophone
    Formant and Resonant
     + SSM-1750 Channel Balance Left Full
     + SSM-1750 Channel Balance Left Half
     + SSM-1750 Channel Balance Right Full
     + SSM-1750 Channel Balance Right Half
     + SSM-1750 Channel Default
     + SSM-1750 Channel High Boost
     + SSM-1750 Channel High Cut
     + SSM-1750 Channel Low Boost
     + SSM-1750 Channel Low Cut
     + SSM-1750 Channel Mid Boost
     + SSM-1750 Channel Mid Cut
     + SSM-1750 Channel Mono
     + SSM-1750 Echo 00 Delay 00 Repeat
     + SSM-1750 Echo 00 Delay 05 Repeat
     + SSM-1750 Echo 00 Delay 10 Repeat
     + SSM-1750 Echo 01 Delay 00 Repeat
     + SSM-1750 Echo 01 Delay 05 Repeat
     + SSM-1750 Echo 01 Delay 10 Repeat
     + SSM-1750 Echo 02 Delay 00 Repeat
     + SSM-1750 Echo 02 Delay 05 Repeat
     + SSM-1750 Echo 02 Delay 10 Repeat
     + SSM-1750 Echo 03 Delay 00 Repeat
     + SSM-1750 Echo 03 Delay 05 Repeat
     + SSM-1750 Echo 03 Delay 10 Repeat
     + SSM-1750 Echo 04 Delay 00 Repeat
     + SSM-1750 Echo 04 Delay 05 Repeat
     + SSM-1750 Echo 04 Delay 10 Repeat
     + SSM-1750 Echo 05 Delay 00 Repeat
     + SSM-1750 Echo 05 Delay 05 Repeat
     + SSM-1750 Echo 05 Delay 10 Repeat
     + SSM-1750 Echo 06 Delay 00 Repeat
     + SSM-1750 Echo 06 Delay 05 Repeat
     + SSM-1750 Echo 06 Delay 10 Repeat
     + SSM-1750 Echo 07 Delay 00 Repeat
     + SSM-1750 Echo 07 Delay 05 Repeat
     + SSM-1750 Echo 07 Delay 10 Repeat
     + SSM-1750 Echo 08 Delay 00 Repeat
     + SSM-1750 Echo 08 Delay 05 Repeat
     + SSM-1750 Echo 08 Delay 10 Repeat
     + SSM-1750 Echo 09 Delay 00 Repeat
     + SSM-1750 Echo 09 Delay 05 Repeat
     + SSM-1750 Echo 09 Delay 10 Repeat
     + SSM-1750 Echo 10 Delay 00 Repeat
     + SSM-1750 Echo 10 Delay 05 Repeat
     + SSM-1750 Echo 10 Delay 10 Repeat
     + Toilet Bowl Closed
    Rooms
     + Old Home AC Intake Vent
     + Old Home Guest Bath Towel Closet
     + Old Home Guest Bath Tub Resonator
     + Old Home Guest Bath
     + Old Home Hallway Far
     + Old Home Hallway Near
     + Old Home Living Room
    Strings
     + Hyper Sustain

**1.2.1** - [2022.12.22] An overcast, moderate December Thursday
<br/>

    More impulses, a retuned piano (sort of), and small memos.
    
    Regarding the new piano impulses, they come from the same Winter upright piano as the
    originals, the first and only piano I've ever owned (as of writing). I spent about 4 hours
    learning how to tune a piano, with mild success. The result is that all the strings now
    roughly hover over a more correct pitch center, and most of the strings are much less
    locally detuned. I didn't get it perfect, however, but I think having IRs that are more in
    tune will be generall much more useful to most people.

    The "Basilica Dome Glass Bowls" come from the bowl-shaped scraps of glass pieces that were
    blown for a section of the dome in the Santa Maria degli Angeli e dei Martiri basilica in
    Rome. They were recorded using a delicately-placed contact mic + a soft and fearful sine sweep.
    Paranoia and respect required that I must absolutely not break or damage the pieces, and so
    especially in the little bowl an aggressive noise floor meant heavy post production, and
    relatively mild results. I still think they're cool though, and someday I'll hopefully revisit
    and make nicer ones.

    Added the following subcategories:
     + Formant and Resonant/Basilica Dome Glass Bowls
     + Strings/Winter Upright/New Retuned
     + Strings/Winter Upright/Original Detuned
    
    Added the following impulse responses:
    Formant and Resonant
     + Basilica Dome Glass Bowls Big
     + Basilica Dome Glass Bowls Little
     + Basilica Dome Glass Bowls Nested
    Strings
     + Winter Upright Closed Bass Sustain
     + Winter Upright Closed Default
     + Winter Upright Closed Sustain
     + Winter Upright Open Bass Sustain
     + Winter Upright Open Default
     + Winter Upright Open Sustain

**1.2.0** - [2022.09.20] A thunderstorm-filled Tuesday
<br/>

    New impulses, new documentation + README changes

    + README now includes the current, latest version in the absense of an embedded changelog.
    + README now includes a contributors section, to be expanded.
    + A new background info document for the new Menorcan bunker impulses courtesy of Gater.

    Added the following category:
    + Rooms/Historical/Menorcan Spanish Civil War Bunkers

    Added the following impulse responses:
    Rooms
    + Bunker 1 Entry Far
    + Bunker 1 Entry Near
    + Bunker 1 Rear Back
    + Bunker 1 Rear Back Center
    + Bunker 1 Rear Center
    + Bunker 1 Rear Front Center
    + Bunker 1 Rear Front
    + Bunker 2 Entry Far
    + Bunker 2 Entry Near
    + Bunker 2 Stair Bottom
    + Bunker 2 Stair Top
    Utility
    + Unit Silence

**1.1.1** - [2022.09.11] The Sunday afternoon after
<br/>

    A proper license has been decided!

    And it's the MIT License:
    + Added License.md containing the license agreement for the usage of this library.
    + Separated the INFO + AGREEMENT section into new Info, Sentiment, and License sections.
      Info gives an overview and some technical info, while sentiment offers some of the
      purpose and decision-making insight. License links the user to the new License.md file.
    
    To briefly mirror why this license was chosen, as is discussed in the new sentiment
    section, I felt its balance of permissiveness and legal clarity suited the project well.

    No attribution and the ability to modify and allow commercial use are important to me,
    and I want others to be aware of that. This license allows that and is familiar to many
    which will hopefully make the intent understood. The agreement until now that I have
    included felt like it was headed in this direction, and needed some clarity.

**1.1.0** - [2022.09.10] An hot and rainy Saturday
<br/>

    Quality of life improvements, and new sounds!

    + README now includes approximate file size and additional info about the project scope.
    + The changelog has been separated into a new markdown document, the README will now link
      to the changelog via a relative link at the header where the changelog previous was.
    - Adjusted directory structure, removing the separation of IR file formats by folders
      and opting to move them up to root level. The presets are still separated in folders
      one layer deep. This makes perusing both raw audio and presets easier in the browsers
      of most convolvers, so incompatible files may be ignored and extra folders don't
      appear when unnecessary.
    + Prefaced IR subcategory types to include names, as to make all impulse file folders
      adjacent while grouped with preset folders (Conner Plate I/Impacts > ../Plate I Impacts)
    + Addition of .gitignore, now no longer including some hidden macOS files such as those
      prefixed with ._ and .DS_Store

    Added the following categories and subcategories:
    + Outdoors/Public
    + Outdoors/Public/Bower Ponds
    + Outdoors/Public/Playgrounds
    + Rooms/Commercial/Craft Coffee Shop
    + Rooms/Historical/Drumheller's Little Church
    + Rooms/Historical/Sunnybrook Farm Willowdale Church
    + Synthesized/Decaying
    + Synthesized/Gated

    Fixed and renamed the following broken impulse responses:
    Strings
    + Sustain 1 iPhone -> Winter Upright Damper 2
    + Sustain 2 iPhone -> Winter Upright Damper 3

    Added the following impulse responses:
    Outdoors
    + Bower Ponds Amphitheatre Stage
    + Playground Slide 1
    Rooms
    + Craft Coffee Shop Afar
    + Drumheller's Little Church
    + Sunnybrook Farm Willowdale Church

**1.0.1** - [2022.09.08] The same Thursday, a little later
<br/>

    A Tiny lil update!
    
    + Minimal README polishes to migrate from txt to md format.
    + Removed macOS-exclusive base files
    
    Renamed the following impulse responses:
    Smartphone Speaker Dispersion -> Smartphone 1 Speaker Dispersion   
    
**1.0.0** - [2022.09.08] A warm but rainy autumnal Thursday.
<br/>

    First official release including a changelog!
    
    Added the following categories and subcategories:
    + Enclosed Spaces
    + Enclosed Spaces/2002 Sedan
    + Esoteric Hardware/RadicalShack SSM-1750
    + Esoteric Hardware/Railings
    + Esoteric Hardware/Rusty Steel Sheet
    + Formant and Resonant
    + Formant and Resonant/Breathy Vowels
    + Formant and Resonant/Instrumental Resonance
    + Formant and Resonant/Talkbox
    + Outdoors/Commercial/Gas Stations
    + Outdoors/Commercial/Loading Docks
    + Outdoors/Commercial/Theme Parks
    + Outdoors/Commercial/Universities
    + Outdoors/Residential/Apartments
    + Outdoors/Residential/Apartments/Suburban Apartments
    + Rooms/Commercial/Hotels/Hotel Rooms
    + Rooms/Residential/Villa 10
    + Speakers/Rotary
    + Speakers/Rotary/Rotary L 984
    + Speakers/Telephones
    + Synthesized
    
    Updated the following categories and subcategories:
    + Esoteric -> Esoteric Hardware
    + Outdoors/Residential/Rome Apartment Alley -> ../Apartments/Rome Apartment Alley
    + Rooms/Residential/Unknown House -> Unknown Houses
    
    Added the following impulse responses:
    Enclosed Spaces
    + 2002 Sedan Front
    + 2002 Sedan Rear
    Esoteric Hardware
    + Conner Time Cube
    + Power Down 1
    + Power Down 2
    + Power Down Stereo
    + Garage 1 Stairwell Rail
    + Rusty Steel Sheet
    Formant and Resonant
    + Breathy Ahh Wide
    + Breathy Ohh Wide
    + Burst Flute
    + Burst Trombone
    + Burst Trumpet
    + Kalimba Resonance Contact
    + Kalimba Resonance Full
    + Kalimba Resonance SDC
    + Metallophone Reso Tubes
    + Piezo Autoharp
    + Piezo Guitar
    + Piezo Hi-Hat
    + Piezo Snare Batter
    + Piezo Snare Bottom
    + Piezo Snare Steel Rim
    + Violin Body Dampened
    + Violin Body Resonant
    + Talkbox Aah
    + Talkbox Ahh
    + Talkbox Ayy
    + Talkbox Eee
    + Talkbox Ehh
    + Talkbox Ihh
    + Talkbox Ohh
    + Talkbox Ooh
    + Talkbox Rrr
    + Talkbox Uhh
    + Talkbox Uuu
    + Talkbox Full
    Outdoors
    + Gas Station 1 Car Wash
    + Gas Station 2 Overhang
    + Theme Park Employee Garage
    + University Garage 1 Ramp Above
    + University Garage 1 Stairwell
    + University Garage 2 Stairwell
    + University Garage 3 Outdoor Stair Close
    + University Garage 3 Outdoor Stair Far
    + University Garage 3 Ramp Above
    + University Garage 3 Ramp Bottom
    + University Garage 3 Ramp Middle
    + Suburban Apartment 1 Avenue Slap
    Rooms
    + Lux Hotel Bathroom
    + Reflective Half Bathroom
    + College Master Bedroom
    + College Master Bathroom
    + College Office
    + Garage Bang Snap Far
    + Garage Bang Snap Near
    + Villa 10 Hall Distant
    Speakers
    + Rotary L 984 Full 1 (N)
    + Rotary L 984 Full 2 (NE)
    + Rotary L 984 Full 3 (E)
    + Rotary L 984 Full 4 (SE)
    + Rotary L 984 Full 5 (S)
    + Rotary L 984 Full 6 (SW)
    + Rotary L 984 Full 7 (W)
    + Rotary L 984 Full 8 (NW)
    + Rotary L 984 Swirl
    + Smartphone Speaker Dispersion
    Strings
    + Winter Upright Piano Damper 1
    + Winter Upright Sympathetic Resonance
    Synthesized
    + Dream Throb
    + Shimmerstorm
    + Synthetic Resonance

**0.0.0** - [Pre-History] Before the dawn of time (of this repo)
<br/>

    All items contained in this collection prior to succeeding
    revisions denoted above :)
