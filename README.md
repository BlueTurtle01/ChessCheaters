# ChessCheaters
PySpark code to detect cheaters in Chess.

## What does this repo do?
Using Spark and SQL I created a script that will complete multiple analyses on the Lichess dataset to find evidence that a person may have cheated. It looks for unusual play activity contigent on their current rating, their opening play, and how often they beat a substantially better rated player.

## What I learnt from this project
This is my first project using Spark alongside GCP. I found the speed of both of these incredible and comparing the runtimes for Spark versus conventional Python for the same task was eye-opening to see the speed increase of Spark. This made me realise the necessity of Spark in my future projects where some things may have been impossible with normal Python, which would have then left many doors closed and unexplored.

## What I struggled with / need to improve.
I got stuck using larger datasets with Spark as it took an incredibly long time to analyse even moderate files. Files around 150MB completed in < 10 seconds but a file of 180MB would not complete even after an hour. I think it is unlikely this small increase in size changed the complexity so drastically and hence the problem must lie in my knowledge. I look forward to figuring this problem out though.
