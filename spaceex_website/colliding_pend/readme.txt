This example consists of two colliding penduli of equal mass. 

There are two versions:
- sys2 : The penduli touch when at rest. This setup shows a simple periodic behavior.
         If initially only one pendulum is displaced and the other is at rest, then the
         energy is passed completely from one to the other at the time of collision.
         Consequently, only one of the penduli swings at a time.
         
- sys2_spaced : There is a gap between both penduli. The resulting behavior is irregular.
         At times, the penduli barely touch, which generates a sliding-mode like series
         of almost-collisions that are hard for reachability.
         
The configuration files are as follows:
- no_gap_between : The penduli touch when at rest. Initially, the right pendulum is 
		 displaced.
- no_gap_between_timed : As no_gap_between but with a timer that stops at 60s.
- with_gap_between : The penduli with gap. Initially, the right pendulum is 
		 displaced.
- with_gap_between_timed : As with_gap_between but with a timer that stops at 60s.
