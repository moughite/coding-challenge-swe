# Coding Challenge [SWE] @ Memberspot

## Incentive

This Task will touch on a couple of core concepts, which you will come acorss when working with a Typescript project at Memberspot

## Challenge

Write a small application which fetches data from an API (I'd choose [this one](https://www.swapi.tech/documentation)) and display it in a paginated list.

### Requirements

1. diplay a list of data with at least 4 fields
   1. the list should at least 1 aggregated value
   1. in case of the [example API](https://www.swapi.tech/documentation), display a persons _name_, _birth_year_, _homeworld_ and the homeworlds _terrain_
1. implement an input above the list to **case insensitive**
   filter the data
1. the list should be paginated, page size 10 (_lazyloading_ is preferred over "traditional pages")
1. have some fun and be creative

### Notes and hints

0. You are free to choose whatever technology you want, but...
1. As a company we have a decided on a tech-stack already
   1. Angular for client-side apps
   1. nestjs for server-side apps
   1. tailwind
2. use an api
   1. if it is public, try to **cache** you data and make **as few requests** as possible
   1. feel free to build your own
3. if you want to mock a database, use a json file and load it into memory
4. please use `strict` mode in your tsconfig

### Submitting

1. Fork this repo and create a pull request
2. notify Memberspot

## Alternatives

If you do not have time for a take home assignment, let us know!
In this case we would try to implement parts of it live in a technical interview

If you have a project to which you contribute regularly, when can also talk about that.
We are interested in your work.
