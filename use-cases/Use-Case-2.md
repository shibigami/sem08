# USE CASE: 2 Produce a Report of the population of cities in the world, continent, region, country and district

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *User* I want *the population of cities in the world, continent, region, country and district organised by largest to smallest* so that *I can create a report for my organisation.*

### Scope

Organisation.

### Level

Primary task.

### Preconditions

Database contains current population data of cities in the world, continent, region, country and district.

### Success End Condition

A report for population in the world, continent, region, country and district has been created.

### Failed End Condition

No report is produced.

### Primary Actor

User.

### Trigger

Organisation wants a report for the current population of cities.

### MAIN SUCCESS SCENARIO

1. Organisation request a report for current population of cities.
2. System provides requested data
3. User extracts current population information from the system.
4. User provides report to organisation.

### EXTENSIONS

3. **Database does not connect**:
    1. User informs developer that database is not connecting.

### SUB-VARIATIONS

None.

### SCHEDULE

**DUE DATE**: Release 1.0