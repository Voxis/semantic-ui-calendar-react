# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).

## [Unreleased](https://github.com/arfedulov/semantic-ui-calendar-react/compare/v0.7.0...HEAD)

## [v0.7.0](https://github.com/arfedulov/semantic-ui-calendar-react/compare/v0.6.0...v0.7.0) - 2018-07-22

### Commits

- feat: `disable`, `minDate`, `maxDate` attributes [`af0d3a9`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/af0d3a91933903f5fc82fee83e5a0499f44f544f)
- feat: add `initialDate` attribute [`23e8008`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/23e800851716e0645451c99f2e0084937747a4c6)
- docs: correct README [`273d8eb`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/273d8eb576e3664b5de7ebd837a53b78c0d9a86a)
- chore: remove propTypes from production build [`e3f7820`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/e3f782017cafdf7b032054594d124ec45cab2343)
- fix(DatesRangeInput): clear selected range if `value` is empty [`3b57013`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/3b57013f3f8bd56092c7612f965894f4efc5109e)

## [v0.6.0](https://github.com/arfedulov/semantic-ui-calendar-react/compare/v0.5.0...v0.6.0) - 2018-06-30

### Merged

- fix: #13 input element updates only on `value` prop change [`#14`](https://github.com/arfedulov/semantic-ui-calendar-react/pull/14)

### Commits

- fix: doesn't work with React 15 [`40dd5df`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/40dd5df41396c38f2edeb1493ff6c25748835f7e)
- feat: close popup on date/time selected [`9cc79c0`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/9cc79c0c9802425f95828173a56d57160faabc4e)

## [v0.5.0](https://github.com/arfedulov/semantic-ui-calendar-react/compare/v0.4.6...v0.5.0) - 2018-06-11

### Commits

- refactor: lift state to input elements [`513d7f5`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/513d7f53b03c683cb8b47515f90cd5490314719e)
- refactor: updateProptypes [`b747b26`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/b747b26c3ec577f9562480d72a915ff0d6362769)
- fix: IE Event constructor [`74ee3a4`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/74ee3a42d26ebb2ef5ade78fd69323de21b1c2de)
- fix: DateInput invalid date parsing [`380f644`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/380f644b519d6e595e49f1a28c423ff819810773)
- fix: TimeInput switch modes [`9b48376`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/9b48376d8a0ddcc456cfa31ab12628765b89986f)

## v0.4.6 - 2018-06-05

### Merged

- Typescript definitions [`#10`](https://github.com/arfedulov/semantic-ui-calendar-react/pull/10)
- add unhandled props to callback data [`#12`](https://github.com/arfedulov/semantic-ui-calendar-react/pull/12)
- fix: correctly parse custom dateFormats in DateInput and DateTimeInput [`#9`](https://github.com/arfedulov/semantic-ui-calendar-react/pull/9)
- feat: inline inputs [`#8`](https://github.com/arfedulov/semantic-ui-calendar-react/pull/8)
- feat: startMode support on Date/DateTimePicker [`#7`](https://github.com/arfedulov/semantic-ui-calendar-react/pull/7)
- fix: #4 input value formatting using props [`#5`](https://github.com/arfedulov/semantic-ui-calendar-react/pull/5)
- breaking: change input elements onChange callbacks [`#3`](https://github.com/arfedulov/semantic-ui-calendar-react/pull/3)

### Commits

- fix: fill dates range input with empty string when it's empty [`3297836`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/3297836dcd77e95678ea8283503c384765bcff33)
- perf: avoid unnecessary `Picker` update [`b883413`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/b8834139e5870d00db031093f057bf7f4ff14aeb)
- fix: popup content goes outside it's border [`068789c`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/068789c4c00b01e21d3c64e8e2a023da39d6a3da)
- docs: change examples in README [`7a393bd`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/7a393bd8893439582f7a6c08900602cc7ab16548)
- chore: split assets building on subtasks [`9e3cdb6`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/9e3cdb6e4e77959aed25df318f62b628e2051171)
- fix: update type definitions [`3915378`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/39153786771330a6cd4362723bcfc0c8be1b9787)
- refactor: use one tick delay instead of controlled popup [`31c87e5`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/31c87e583396cc3ebd5b8ed3ea9fb89aec6e3300)
- fix: popup doesn't close on click in IE 11 [`3d47765`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/3d4776518d2d96caef4880f745802f6544234a8e)
- fix: popup does not close  on scroll [`819bc06`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/819bc06f337145763149ce113a88d84de567a44b)
- fix: doesn't switch years on next/prev btn click in month mode [`fc2c374`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/fc2c374c04baca6072562e93e3960032e9acc2ba)
- fix: popup doesn't close on document click [`92abd5f`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/92abd5f62ba28061a60d25089c73cd9e0b0b730a)
- refactor: get rid of BasePicker [`2a42230`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/2a42230ce0e77953aafbbe61da9bd147ac25a92d)
- chore: update dependencies [`0c75da9`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/0c75da901f4144408d176cd8b9e6ff8209adfc74)
- feat: switch mode on header click [`a3bbfc2`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/a3bbfc24aa231c3bdc550feb481148ab91265a4c)
- fix: does not work on IE 11 [`8f6244b`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/8f6244bdefa5cacbef686a218879ad8b91773577)
- chore: update version [`187d1d7`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/187d1d70ff5239c9a84e986abfc07269542c0ab6)
- fix: nested tables [`9a27ec1`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/9a27ec146a0bff0c10cfe525bc3b936dce2ec22a)
- feat: add popupPosition prop to input elements [`90d60ac`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/90d60ac15b78bf763373192e5528656002c698b2)
- refactor: move shared pickers methods in BasePicker class [`819fbc0`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/819fbc045a60778baeabd3c0b602cf0ca9da0881)
- feat: MonthInput [`517f6ae`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/517f6aef0b1daed8219a3ea297e117036677b986)
- feat: YearPicker [`792e916`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/792e91655a001e440b348d3514eae4798e8020f3)
- chore: update version [`cd5c49b`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/cd5c49b386b955bca4cdad26f0efc2fa33657592)
- refactor: make input components interface more resembling SUIR Input's interface [`b5160ff`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/b5160ffdae0d8667eea691f77490fdc74077b1a2)
- chore: update version [`9211f27`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/9211f275af19ab4a26e942762bdb5b3fe8532157)
- merge dateRange [`ecb0896`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/ecb0896b8044504d91932a0ca31649abbce2981c)
- add: DatesRangeInput [`ddf34b1`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/ddf34b182ab8cf649ea77fd95005f5979e33ffda)
- fix: #1 timepicker popup closes automatically before a value is accepted [`068de87`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/068de872cdb398ef0e7e5317b67caa8ccf8359f6)
- fix: cant fill input field using keyboard or erase it [`11cc759`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/11cc759ad1d45fce290837322939fd14d52aa3b3)
- refactor: use getUnhandledProps to pass unhandled props down [`730f476`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/730f476bd8fbbb5b8f7b711d14f02d8016bd524b)
- docs: ad d js syntax highlighting to README [`4303665`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/430366526aa558d5921ee76c996d37211f626982)
- docs: update README [`08efe06`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/08efe06dbfa1b1f41ccf50cfa1180f69206f128d)
- add: form input examples [`3a1f962`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/3a1f962d0904f8439fde06b5d508e10d676916e9)
- add: DateInput TimeInput DateTimeInput [`55e22de`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/55e22deaed3afd0aab81238b63d6c593ad105049)
- fix: DateTimePicker's prev/next buttons dont work [`e0a040e`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/e0a040e7ecf7e907684e19f8d23d544b0ca88fdd)
- add: DatePicker TimePicker DateTimePicker [`d911f09`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/d911f090f71e56a2c785404291cb85ce16379ef4)
- chore: update package.json [`87bafd0`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/87bafd06b592dfd688389da1ab076f57aa4e7d78)
- add: build script [`c832768`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/c83276876589b2ba96523f9284b3664c80f10e40)
- add: CalendarContainer [`f10fed3`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/f10fed3f56ac5f6bdd73fc3b1e9940f37d1967c9)
- add: css [`bbe9e30`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/bbe9e3011e0462acb0865352759e49fbf53838ac)
- update(Calendar): complete component's interface [`2d83c7d`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/2d83c7dc2384d61efebb98555af722fb7152e86a)
- Create README.md [`5df3058`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/5df3058b02b36e79d6f7b12eb8d3729a4b506341)
- Initial commit [`0d101f9`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/0d101f97eef7df1630eb7839131ce962f945b8fc)
- add: Calendar component [`186490b`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/186490b52febf12d65ba834e5945764eb3c17adf)
- initial [`995c011`](https://github.com/arfedulov/semantic-ui-calendar-react/commit/995c01189426ebc5db2ade83edfeb27745699bbe)