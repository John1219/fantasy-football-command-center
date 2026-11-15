# Fantasy Football Command Center

A private, personal analytics dashboard for my own Yahoo Fantasy Football
leagues. Built and used by one person (me) for personal, non-commercial use.

## What it does

- Shows standings and team pages for my three Yahoo Fantasy Football leagues
  (Big Money League Yr 25, CFFC Champions League, Killer Pit Yr22)
- Computes player rankings under each league's own scoring rules, rather than
  a generic scoring system
- Analyzes roster strengths, weaknesses, and positional needs for every team
  in those leagues
- Tracks weekly scoring trends for top players in each league

## Data access

The tool is designed to read my own league data (league settings and scoring,
standings, rosters, transactions, and player status) through the Yahoo Fantasy
Sports API using read-only access (Fantasy Sports Read permission), after
Yahoo's approval of my API access application. It never writes to Yahoo, never
modifies a league, and no data is published, shared, sold, or shown to any
other person.

## Use

Single user only: the owner of the leagues above. Request volume is low
(a few dozen read calls per day at most). There is no public deployment,
no app store listing, and no third-party access of any kind.
