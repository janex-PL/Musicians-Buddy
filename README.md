# Musician's Buddy
This project contains backend structures and functions mainly for musical chord recognition, that will probably be used in a future site/app.

# Planned features

 - Converting list of notes to a specific chord/list of matching chords

  Function will accept a list of notes (pitch and its octave) and will find a chord that will be the best match or will give list of chords, that consist of notes given in the list. Function will return a type of chord and it's key. Additionaly, function will detect the chords inversion and remove notes, that are unnecesery e.g. if there are 2 notes in the same pitch, but different octave, then function will delete one of the notes.
Function will work in 2 modes - "Root note specified" and "Any possible match".


 - Matching chord/list of chords/list of notes to a specific scale/list of matching scales

Function will accept a list of chords and will find a scale with key note, that will be the best match or a list of scales, that consist of chords given in the list.

 - Matching chords to a specific chord progression and/or list of matching progressions
 
Function will accept list of chords and find a chord progression, which will be the best match or a list of progressions, that matches the given chord list. The accuracy will depend on the number of given chords.

 - Generating chords from a specified scale and/or chord progression
 
Function will accept a scale and/or a chord progression and will generate chords, that matches the scale and/or a chord progression.
 
 - Matching notes to a specific scale and/or list of matching scales

Function will accept list of notes to a specific scale or list of matching scales. The accuracy will depend on numbers of given notes.

# Future of the project

This project is just a starting point for an idea that I have in my head right now. Here is the list of ideas/milestones for the project:
- Desktop offline console app, that will function as a helper without storage
- Desktop offline app with GUI, that will function as a helper without storage
- Desktop offline app with GUI, that will function as a helper with local storage
- Desktop online app with GUI, that will function as a helper with local and online storage
- Web app with GUI, that will function as a helper with online storage and local export
- Web platform, which will additionally allow users to interact with each other, chat, share ideas etc.

Those are just some of the ideas, which may change in the future
