Welcome to Repositories in a Bucket!

Every once in a while, I pull a repository from the bucket.
Old repositories that I have picked repositories will be equally likely to be picked.
New repositories (1st 2 times picked) will have 3 times the chance to be picked.

When I take that repository, I conribute to it.
You can find the times that it's scheduled to happen in schedule.txt.

To enter a repository, read README_entries.txt
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

Some projects that, quoteonquote, "need my help" are automatically entered unless Manual Only is set to true. These repositories can be found
  in auto.txt
In order for your account to be checked for WillboxMattewRepositoriesInABucket, this repository mus be starred. Once your name is registered,
  you can unstar. To have your account pulled from the list, read README_requests.txt.

I'm probably going to hold out on this a long time, but at least you'll be prepared.

-WillboxMattew
