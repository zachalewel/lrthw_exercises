(104389692_chapter1_master) Zach Alewel
Zachs-MacBook-Pro:chapter_1 $ guard
10:05:02 - INFO - Inspecting Ruby code style of all files
Inspecting 2 files
CC

Offenses:

ex1.rb:1:6: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
puts "Hello World!"
     ^^^^^^^^^^^^^^
     ######Here guard is letting me know I can use `''` instead
ex1.rb:2:6: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
puts "Hello Again"
     ^^^^^^^^^^^^^
     ######Here guard is letting me know I can use `''` instead
ex1.rb:3:6: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
puts "I like typing this"
     ^^^^^^^^^^^^^^^^^^^^
     ######Here guard is letting me know I can use `''` instead
ex1.rb:4:6: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
puts "This is fun."
     ^^^^^^^^^^^^^^
     ######Here guard is letting me know I can use `''` instead
ex1.rb:5:6: C: Prefer single-quoted strings when you don't need string interpolation or special symbols.
puts "Yay! Printing."
     ^^^^^^^^^^^^^^^^
     ######Here guard is letting me know I can use `''` instead
ex1.rb:8:1: C: 1 trailing blank lines detected.
2 files inspected, 6 offenses detected

10:05:02 - INFO - Guard is now watching at '/Users/zachalewel/workspace/davinci_coders_t3_2015/homework/lrthw_exercises/chapter_1'
[1] guard(main)>


I added  ` - "''"` in the .rubocop.yml file in my master branch then I pushed that to github.
and now it doesn't care about the " or ' 
