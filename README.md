# Mynah-Ortolan
### Tonal Harmony Figured Bass Automation


Languagues: Python 3, LilyPond


Outline:

Music notation input (as data) //Make the notation UI clickable for input 
Calculate 
Output result


Rules:

{

1a. NO consecutive 5ths
1b. NO consecutive octaves

} //For all
1c. NO hidden (or “exposed”) consecutives



2a. NO dissonant leaps (seventh, augmented or diminished intervals), choose small intervals. Leading note resolves to the tonic.

No leaps of a seventh
No Augmented 2nds and 4ths
In major keys, diminished/augmented melodic intervals are NOT recommended. // That means it’ll need to be able to identify the Key, which is what a human would do for the first step
6ths should be avoided. //it’s ok especially soprano
Leading notes in dominant chords ALWAYS resolve onto the tonic of a tonic chord. (Bach didn't always do this, though!) // advanced search 
In a cadential 6-4, the 4 resolves to 3 and the 6 resolves to 5.
Always choose a semitone step if one is available.
2b. The soprano line should have an interesting melody.
2c. The alto and tenor lines should not move about much at all.

//Always choose the nearest note that you can, without breaking any other rules

2d.  Bass line // write if given soprano only

The bass line should be reasonably melodic, without too much repetition of adjacent notes.

The bass usually moves either by step, or by leaps of perfect 4ths and 5ths, or by leaps of 3rds. Octave leaps may be used in moderation.

The bass should not leap by a 7th, an augmented or a diminished interval.

The final note in the bass line of a piece must always be the tonic.





3a. Double the root or fifth in root position chords. Double any note in first inversion chords. Double the fifth in second inversion chords. Double the third in diminished chords. Double the third with care in other chords.

Generally the 3rd is the least satisfactory note to double, but there are some exceptions.

 

You may double the Root:

In any 5-3 chord
In any 6-3 chord EXCEPT diminished chords (ii° or vii°)
Never in 6-4 chords
 

You may double the Third:

In any 6-3 chord EXCEPT if it is the leading note (which means chord Vb)
Never in 6-4 chords
Never in a 5-3 chord UNLESS:
it is a minor third and it’s your only choice
it is a major third AND the piece is in a minor key, AND it’s part of a V-VI progression.
 

You may double the Fifth:

In any 5-3 chord
In any 6-3 chord EXCEPT diminished chords (ii° and vii°)
Always in 6-4 chords
 

Use this table for reference while you’re practising. The greyed out chords are not used in tonal harmony at grade 6.

The chord notes in brackets are OK but try not to use them unless you absolutely have to!

 


3b. Never leave out a figured note. Never leave out the root or third.

Generally the 3rd is the least satisfactory note to double, but there are some exceptions.

 

You may double the Root:

In any 5-3 chord
In any 6-3 chord EXCEPT diminished chords (ii° or vii°)
Never in 6-4 chords
 

You may double the Third:

In any 6-3 chord EXCEPT if it is the leading note (which means chord Vb)
Never in 6-4 chords
Never in a 5-3 chord UNLESS:
it is a minor third and it’s your only choice
it is a major third AND the piece is in a minor key, AND it’s part of a V-VI progression.
 

You may double the Fifth:

In any 5-3 chord
In any 6-3 chord EXCEPT diminished chords (ii° and vii°)
Always in 6-4 chords
 

Use this table for reference while you’re practising. The greyed out chords are not used in tonal harmony at grade 6.

The chord notes in brackets are OK but try not to use them unless you absolutely have to!



3c. It’s ok to omit the 5th

Sometimes it’s ok to leave out the fifth of the triad.

Never leave out a note that is figured. So, if you see “5-3”, you must include the third and the fifth. But if the chord is blank, it means you can leave out the fifth.
If you see “6-3”, you must include the fifth (it’s the “3” of the 6-3), but if you see just “6”, then you can leave out the fifth.

You can never leave out the fifth of a 6-4 chord.

Never leave out the third or the root.



4a. Never overlap parts. //crossed //It’s ok if bass = tenor sometimes
4b. Stay in the accepted voice ranges and don’t put more than an octave between the upper voices.



show error if low note not a chord note


