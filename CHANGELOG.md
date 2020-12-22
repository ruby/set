# Set Changelog

# 1.0.1 (2020-12-22)

* Enhancements
  * Eliminate warnings

# 1.0.0 (2020-12-21)

This is the first release of set as a gem.  Here lists the changes since the version bundled with Ruby 2.7.

* Breaking Changes
  * SortedSet has been removed for dependency and performance reasons. [#2][] ([@knu][])

* Enhancements
  * Set#join is added as a shorthand for `.to_a.join`. [#4][] ([@marcandre][])
  * Set#<=> is added. [#5][] ([@marcandre][])

[#2]: https://github.com/ruby/set/pull/2
[#4]: https://github.com/ruby/set/pull/4
[#5]: https://github.com/ruby/set/pull/5

[@knu]: https://github.com/knu
[@marcandre]: https://github.com/marcandre
