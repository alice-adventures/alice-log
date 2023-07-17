# alice-log
Registry of Participants activities.

The file `participant.log` contains one entry per line of the form

> `date; source; user; id; ref; action`

where:

  * `date` is the date and time (UTC)
  * `source` is the name of the Problem Source, e.g. `project_euler`
  * `user` is the Participant' GitHub login
  * `id` is the number of the puzzle
  * `ref`is the reference (short name) of the puzzle
  * `action` is the action performed, and can be:
    * `publish`: the Participant has published a (new) solution
    * `share`: the Participant has shared (new) stuff for the puzzle
