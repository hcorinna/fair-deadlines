## Fair Deadlines

Countdown timers to keep track of a bunch of fair-ML / AI ethics / computational social science conference deadlines.

## Contributing

Contributions are very welcome!

To add or update a deadline:
- Fork the repository
- Update `_data/conferences.yml`
- If it is a conference (): Make sure it has the `title` (abbreviation), `year`, `id`,  `name` (full name), `link`, `deadline`, `timezone`, `date`, `start`, `place`, `sub`, `cat: conference` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
    + In case the conference is not happening online, add the `flag` attribute. Use the flag unicode, which you can for example find [here](https://openmoji.org/).
- If it is a special issue: Make sure it has the `title`, `year` (only used for calendar entry), `id`,  `name` (journal name), `link`, `deadline`, `timezone`, `start` (same as deadline), `sub`, `cat: specialissue` attributes
- Optionally add a `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline
- Send a pull request

## Local setup

Assuming you have [Ruby](https://www.ruby-lang.org/en/downloads/) and [Bundler](https://bundler.io/) installed on your system (*hint: for ease of managing ruby gems, consider using [rbenv](https://github.com/rbenv/rbenv)*), do the following:

```bash
$ cd <your-repo-name>
$ bundle install
$ bundle exec jekyll serve
```

## Origin

This is a fork of [aideadlin.es][2] by [@abhshkdz](https://github.com/abhshkdz)

## Forks & other useful listings

- [geodeadlin.es][3] by @LukasMosser
- [neuro-deadlines][4] by @tbryn
- [ai-challenge-deadlines][5] by @dieg0as
- [CV-oriented ai-deadlines (with an emphasis on medical images)][8] by @duducheng
- [es-deadlines (Embedded Systems, Computer Architecture, and Cyber-physical Systems)][9] by @AlexVonB and @k0nze
- [2019-2020 International Conferences in AI, CV, DM, NLP and Robotics][10] by @JackieTseng
- [ccf-deadlines][11] by @ccfddl
- [netdeadlines.com][12] by @albertgranalcoz

## License

[MIT][1]

[1]: https://abhshkdz.mit-license.org/
[2]: https://aideadlin.es/
[3]: https://github.com/LukasMosser/geo-deadlines
[4]: https://github.com/tbryn/neuro-deadlines
[5]: https://github.com/dieg0as/ai-challenge-deadlines
[6]: http://www.conferenceranks.com/#
[8]: https://creedai.github.io/ai-deadlines/
[9]: https://ekut-es.github.io/es-deadlines/
[10]: https://jackietseng.github.io/conference_call_for_paper/conferences.html
[11]: https://ccfddl.github.io/
[12]: https://netdeadlines.com/
