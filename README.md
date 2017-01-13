# Results of NFL games in CSV format taken from: https://github.com/devstopfix/nfl_results

## Format

Each file is in [Comma-Separated Value](http://en.wikipedia.org/wiki/Comma-separated_values) format with the following columns:

| Column         | Format                                                   | Example
| -------------- | -------------------------------------------------------- | -----------
| season         | Number (4 digits)                                        | 2010
| week           | The week number since opening day (1-22)                 | 1
| kickoff        | [ISO 8601](http://en.wikipedia.org/wiki/ISO_8601) format | 2010-09-09T20:30-05:00
| home_team      | Team name, without city                                  | Saints
| home_score     | Number                                                   | 14
| visitors_score | Number                                                   | 9
| visiting_team  | Team name, without city                                  | Vikings


### Kickoff

This column will hold the date and time of the kickoff in [Eastern Time](http://en.wikipedia.org/wiki/Eastern_Time_Zone) if it is known (e.g. 2010-09-09T20:30:00-05:00) otherwise it will just hold the date of the match with the time set to midnight.


# License

This data is made available under the [Public Domain Dedication and License version v1.0](http://opendatacommons.org/licenses/pddl/) whose full text can be found at http://opendatacommons.org/licenses/pddl/
