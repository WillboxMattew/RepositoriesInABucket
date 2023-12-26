To submit contributions, make a fork of this repository, name it WillboxMattewRepositoriesInABucket, add another branch,
  and put the names of the repos you want to enter in a JSON file named entries.json (following format:)

{
"repeat":
["(Repository Name)","(Repository Name)",],
"spec":
{
"(Repository name)":
[[(First), (Second),],(Once),],
"(Repository name)":
[[(First), (Second),],(Once),],
},
"manualOnly":(Boolean)
}

It is included in this repository, so it is copied when you fork it. These projects are found in auto.txt.

Repeat is for something you want to enter every time (subscribed), but Spec is specific times. Fill (First), (Second), and (Once) with numbers;
  every time this event happens, the number increases by one, then a program finds matches.
