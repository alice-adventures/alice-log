# alice-log
Registry of Participants activities.

Each log file refers to a particular Problem Source. Each line contains one entry of the form

>  `date; user; id; ref; action; <others>`

where:

  * `date` is the date and time (UTC)
  * `user` is the Participant' GitHub login
  * `id` is the number of the puzzle
  * `ref`is the reference (short name) of the puzzle
  * `action` is the action performed, and can be:
    * `publish`: the Participant has published a (new) solution
    * `share`: the Participant has shared (new) stuff for the puzzle
  * `<other>` is a set of additional fileds that depend on each Problem Source
    * e.g., for `project_euler` there is a field `type` with possible values `cli` or `gui`
