Title: This Week in Rust 604
Number: 604
Date: 2025-06-18

Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](https://www.rust-lang.org/) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tag us at
[@thisweekinrust.bsky.social](https://bsky.app/profile/thisweekinrust.bsky.social) on Bluesky or
[@ThisWeekinRust](https://mastodon.social/@thisweekinrust) on mastodon.social, or
[send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust) and archives can be viewed at [this-week-in-rust.org](https://this-week-in-rust.org/).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

Want TWIR in your inbox? [Subscribe here](https://this-week-in-rust.us11.list-manage.com/subscribe?u=fd84c1c757e02889a9b08d289&id=0ed8b72485).

## Updates from Rust Community

<!--

Dear community contributors:
Please read README.md for guidance on submissions.
Each submitted link should be of the form:

* [Title of the Linked Page](https://example.com/my_article)

If you don't know which category to use, feel free to submit a PR anyway
and just ask the editors to select the category.

-->

### Official
* [Rust compiler performance survey 2025](https://blog.rust-lang.org/2025/06/16/rust-compiler-performance-survey-2025/)
* [June 2025 Leadership Council Update | Inside Rust Blog](https://blog.rust-lang.org/inside-rust/2025/06/11/leadership-council-update/)

### Foundation
* [Announcing the RustConf 2025 Speaker Lineup](https://rustfoundation.org/media/announcing-the-rustconf-2025-speaker-lineup/)

### Newsletters
* [This Month in Rust OSDev: May 2025](https://rust-osdev.com/this-month/2025-05/)

### Project/Tooling Updates
* [rust-analyzer changelog #290](https://rust-analyzer.github.io/thisweek/2025/06/16/changelog-290.html)
* [Linebender in May 2025](https://linebender.org/blog/tmil-17/)
* [bzip2 crate switches from C to 100% rust](https://trifectatech.org/blog/bzip2-crate-switches-from-c-to-rust/)
* [Hypershell: A Type-Level DSL for Shell-Scripting in Rust](https://contextgeneric.dev/blog/hypershell-release/)
* [Slint 1.12 Released with WGPU Support, iOS Port, and Figma Variables Integration](https://slint.dev/blog/slint-1.12-released)
* [Glues v0.7.0 – TUI Note-Taking App with a New Theme Engine & Color Palettes](https://github.com/gluesql/glues/releases/tag/v0.7.0)

### Observations/Thoughts
* [retrobootstrapping rust for some reason](https://graydon2.dreamwidth.org/317484.html)
* [The plight of the misunderstood memory ordering](https://www.grayolson.me/blog/posts/misunderstood-memory-ordering/)
* [Don't you dare to sort your struct fields when using ?Sized](https://blog.veeso.dev/blog/en/dont-you-dare-to-sort-your-struct-fields-when-using-sized/)
* [audio] [Tembo with Adam Hendel](https://corrode.dev/podcast/s04e05-tembo/)
* [audio] [Rust at Work - conversation with Eli Shalom and Igal Tabachnik of Eureka Labs](https://rustacean-station.org/episode/eli-shalom-and-igal-tabachnik/)
* [video] [sans-io: meh](https://sdr-podcast.com/episodes/sans-io/)
* [video] [Guillaume Gomez - Rustdoc as a case study of developer tooling](https://timclicks.dev/podcast/guillaume-gomez-rustdoc)
* [video] [10th Bevy Meetup - Tristan - From zero to demo: a newcomer's experience learning Bevy](https://www.youtube.com/watch?v=_FIDuLV0ZsA)

### Rust Walkthroughs
* [Putting seat calculations in Dutch election software to the (fuzz) test](https://tweedegolf.nl/en/blog/156/putting-seat-calculations-in-dutch-election-software-to-the-fuzz-test)
* [Datalog in Rust](https://github.com/frankmcsherry/blog/blob/master/posts/2025-06-03.md)
* [video] [Driving an LED matrix using async embedded Rust - moxi Ep2](https://www.youtube.com/watch?v=uZDcWA8cCsw)

### Research
* [Asterinas: A Linux ABI-Compatible, Rust-Based Framekernel OS with a Small and Sound TCB](https://arxiv.org/abs/2506.03876)

### Miscellaneous
* [Making GNOME’s GdkPixbuf Image Loading Safer](https://blogs.gnome.org/sophieh/2025/06/13/making-gnomes-gdkpixbuf-image-loading-safer/)
* [May 2025 Jobs Report](https://filtra.io/rust/jobs-report/may-25)
* [Rust social status update 2025.06](https://rust.code-maven.com/rust-update-2025-06-17)
* [How Rolldown Works: Symbol Linking, CJS/ESM Resolution, and Export Analysis Explained](https://www.atriiy.dev/blog/rolldown-link-stage-symbol-linking-resolution)

## Crate of the Week

This week's crate is [RobustMQ](https://github.com/robustmq/robustmq), a next-generation, high-performance, multi-protocol message queue.

Thanks to [Yu Liu](https://users.rust-lang.org/t/crate-of-the-week/2704/1443) for the self-suggestion!

[Please submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Calls for Testing
An important step for RFC implementation is for people to experiment with the
implementation and give feedback, especially before stabilization.

If you are a feature implementer and would like your RFC to appear in this list, add a
`call-for-testing` label to your RFC along with a comment providing testing instructions and/or
guidance on which aspect(s) of the feature need testing.

* *No calls for testing were issued this week by [Rust](https://github.com/rust-lang/rust/labels/call-for-testing),
  [Rust language RFCs](https://github.com/rust-lang/rfcs/issues?q=label%3Acall-for-testing),
  [Cargo](https://github.com/rust-lang/cargo/labels/call-for-testing) or
  [Rustup](https://github.com/rust-lang/rustup/labels/call-for-testing).*

[Let us know](https://github.com/rust-lang/this-week-in-rust/issues) if you would like your feature to be tracked as a part of this list.

## Call for Participation; projects and speakers

### CFP - Projects

Always wanted to contribute to open-source projects but did not know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

<!-- CFPs go here, use this format: * [project name - title of issue](URL to issue) -->
<!-- * [ - ]() -->
<!-- or if none - *No Calls for participation were submitted this week.* -->

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines] or through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [X (formerly Twitter)](https://x.com/ThisWeekInRust) or [Mastodon](https://mastodon.social/@thisweekinrust)!

[guidelines]:https://github.com/rust-lang/this-week-in-rust?tab=readme-ov-file#call-for-participation-guidelines

### CFP - Events

Are you a new or experienced speaker looking for a place to share something cool? This section highlights events that are being planned and are accepting submissions to join their event as a speaker.

<!-- CFPs go here, use this format: * [**event name**](URL to CFP)| Date CFP closes in YYYY-MM-DD | city,state,country | Date of event in YYYY-MM-DD -->
<!-- or if none - *No Calls for papers or presentations were submitted this week.* -->

If you are an event organizer hoping to expand the reach of your event, please submit a link to the website through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [X (formerly Twitter)](https://x.com/ThisWeekInRust) or [Mastodon](https://mastodon.social/@thisweekinrust)!

## Updates from the Rust Project

461 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2025-06-10..2025-06-17

#### Compiler

* [cache `param_env` canonicalization](https://github.com/rust-lang/rust/pull/141451)
* [early linting: avoid redundant calls to `check_id`](https://github.com/rust-lang/rust/pull/142398)
* [move fast reject into inner](https://github.com/rust-lang/rust/pull/142355)
* [use `MixedBitSet` for borrows-in-scope dataflow analysis](https://github.com/rust-lang/rust/pull/142471)
* [miri: add flag to suppress float non-determinism](https://github.com/rust-lang/rust/pull/142337)
* [miri: we can use apfloat's `mul_add` now](https://github.com/rust-lang/rust/pull/142340)

#### Library

* [stabilize `"file_lock"` feature](https://github.com/rust-lang/rust/pull/142125)
* [stabilize keylocker](https://github.com/rust-lang/rust/pull/140766)
* [add `Vec::peek_mut`](https://github.com/rust-lang/rust/pull/142046)
* [added `Clone` implementation for `ChunkBy`](https://github.com/rust-lang/rust/pull/138016)
* [faster `fmt::Display` of 128-bit integers, without unsafe pointer](https://github.com/rust-lang/rust/pull/136594)
* [add `bit_width` for unsigned integer types](https://github.com/rust-lang/rust/pull/142328)
* [remove unneeded lifetime bound from signature of `BTreeSet::extract_if`](https://github.com/rust-lang/rust/pull/142484)

#### Cargo

* [add custom completer for `cargo remove <TAB>`](https://github.com/rust-lang/cargo/pull/15662)
* [highlight the correct words](https://github.com/rust-lang/cargo/pull/15659)
* [refactor: replace InternedString with Cow in IndexPackage](https://github.com/rust-lang/cargo/pull/15559)

#### Rustdoc

* [Give more information into extracted doctest information](https://github.com/rust-lang/rust/pull/141399)
* [rustdoc\_json: reduce allocations](https://github.com/rust-lang/rust/pull/142335)

#### Rustfmt

* [don't try to repair invalid self-imports](https://github.com/rust-lang/rustfmt/pull/6573)

#### Clippy

* [Optimize 3rd heaviest func, (81b → 10m)](https://github.com/rust-lang/rust-clippy/pull/15043)
* [add lint for broken doc links](https://github.com/rust-lang/rust-clippy/pull/13696)
* [docs: add link to `span_lint` in diagnostics.rs](https://github.com/rust-lang/rust-clippy/pull/15065)
* [docs: make `unbuffered_bytes` docs more consistent](https://github.com/rust-lang/rust-clippy/pull/15019)
* [fix FP of `identity_op` when encountering `Default::default()`](https://github.com/rust-lang/rust-clippy/pull/15028)
* [fix `collapsible_else_if` FP on conditionally compiled stmt](https://github.com/rust-lang/rust-clippy/pull/14906)
* [fix `needless_doctest_main` panic when doctest is invalid](https://github.com/rust-lang/rust-clippy/pull/15052)
* [fix `unit_arg` suggests wrongly for `Default::default`](https://github.com/rust-lang/rust-clippy/pull/14881)
* [fix suggestion-causes-error of `manual_swap`](https://github.com/rust-lang/rust-clippy/pull/14978)
* [fixes `manual_flatten` removes the useless if let](https://github.com/rust-lang/rust-clippy/pull/14861)
* [remove `ClippyCtfe` pass](https://github.com/rust-lang/rust-clippy/pull/14712)
* [remove unneeded lifetime](https://github.com/rust-lang/rust-clippy/pull/15040)

 #### Rust-Analyzer

* [`ItemTree`'s `ItemVisibilities` has no identity, so deduplicate](https://github.com/rust-lang/rust-analyzer/pull/19980)
* [add support for excluding imports from symbol search](https://github.com/rust-lang/rust-analyzer/pull/19996)
* [cleanup incremental tests and verify query executions](https://github.com/rust-lang/rust-analyzer/pull/20006)
* [add the quickfix for increasing visibility of a private field to the private-field diagnostic](https://github.com/rust-lang/rust-analyzer/pull/19945)
* [in "Fill match arms", allow users to prefer `Self` to the `enum` name when possible](https://github.com/rust-lang/rust-analyzer/pull/19939)
* [insert required parentheses when typing `+` in dyn trait type](https://github.com/rust-lang/rust-analyzer/pull/20015)
* [show what cargo metadata is doing in status](https://github.com/rust-lang/rust-analyzer/pull/20014)
* [copy lockfiles into target directory before invoking `cargo metadata`](https://github.com/rust-lang/rust-analyzer/pull/20018)
* [do not force descend into derives for goto IDE features](https://github.com/rust-lang/rust-analyzer/pull/19981)
* [fix comparison of proc macros](https://github.com/rust-lang/rust-analyzer/pull/19983)
* [fix completion with some attribute macros](https://github.com/rust-lang/rust-analyzer/pull/19942)
* [fix proc macro server handling of strings with minuses](https://github.com/rust-lang/rust-analyzer/pull/19970)
* [hide dyn inlay hints for incomplete `impl`s](https://github.com/rust-lang/rust-analyzer/pull/19973)
* [never make type mismatch diagnostic stable, even when there is a fix](https://github.com/rust-lang/rust-analyzer/pull/20022)
* [reload workspaces when cargo configs change](https://github.com/rust-lang/rust-analyzer/pull/20020)
* [support spans with proc macro servers from before the ast id changes](https://github.com/rust-lang/rust-analyzer/pull/19985)
* [generate annotations for macro defined items if their name is in the input](https://github.com/rust-lang/rust-analyzer/pull/19990)
* [idiomatic salsa use for `enum` variants query](https://github.com/rust-lang/rust-analyzer/pull/20007)
* [improve completions in if / while expression conditions](https://github.com/rust-lang/rust-analyzer/pull/20023)
* [optimize `pub(crate)` and `pub(self)` visibility resolution](https://github.com/rust-lang/rust-analyzer/pull/20009)
* [perf: bring back `EMPTY` item tree deduplication](https://github.com/rust-lang/rust-analyzer/pull/19991)
* [provide better incrementality when items are changed](https://github.com/rust-lang/rust-analyzer/pull/19837)
* [simplify and optimize `ItemTree`](https://github.com/rust-lang/rust-analyzer/pull/19982)
* [turn `BlockId` into a `#[salsa::tracked]`](https://github.com/rust-lang/rust-analyzer/pull/19995)
* [use `ThinVec` in `ItemScope` in a couple places](https://github.com/rust-lang/rust-analyzer/pull/19992)

### Rust Compiler Performance Triage

Relatively quiet week, with a few improvements to benchmarks leveraging the new
trait solver.

Triage done by **@kobzol**.
Revision range: [c31cccb7..45acf54e](https://perf.rust-lang.org/?start=c31cccb7b5cc098b1a8c1794ed38d7fdbec0ccb0&end=45acf54eea118ed27927282b5e0bfdcd80b7987c&absolute=false&stat=instructions%3Au)

**Summary**:

| (instructions:u)                   | mean  | range           | count |
|:----------------------------------:|:-----:|:---------------:|:-----:|
| Regressions ❌ <br /> (primary)    | 0.3%  | [0.1%, 0.5%]    | 14    |
| Regressions ❌ <br /> (secondary)  | 0.3%  | [0.1%, 0.5%]    | 52    |
| Improvements ✅ <br /> (primary)   | -0.5% | [-4.8%, -0.1%]  | 68    |
| Improvements ✅ <br /> (secondary) | -4.3% | [-56.5%, -0.1%] | 85    |
| All ❌✅ (primary)                 | -0.4% | [-4.8%, 0.5%]   | 82    |


3 Regressions, 7 Improvements, 4 Mixed; 4 of them in rollups
51 artifact comparisons made in total

[Full report here](https://github.com/rust-lang/rustc-perf/blob/d40fd2e4bd715c7d350d23e0c894f97f915998b6/triage/2025/2025-06-17.md)

### [Approved RFCs](https://github.com/rust-lang/rfcs/commits/master)

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* *No RFCs were approved this week.*

### Final Comment Period

Every week, [the team](https://www.rust-lang.org/team.html) announces the 'final comment period' for RFCs and key PRs
which are reaching a decision. Express your opinions now.

#### Tracking Issues & PRs
##### [Rust](https://github.com/rust-lang/rust/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* [Set MSG\_NOSIGNAL for UnixStream](https://github.com/rust-lang/rust/pull/140005)
* [Reject unsupported `extern "{abi}"`s consistently in all positions](https://github.com/rust-lang/rust/pull/142134)


##### [Cargo](https://github.com/rust-lang/cargo/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc)
* [Add `http.proxy-cainfo` config for proxy certs](https://github.com/rust-lang/cargo/pull/15374)

##### [Rust RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)
* [Declarative `macro_rules!` derive macros](https://github.com/rust-lang/rfcs/pull/3698)
* [Declarative `macro_rules!` attribute macros](https://github.com/rust-lang/rfcs/pull/3697)

*No Items entered Final Comment Period this week for
[Language Reference](https://github.com/rust-lang/reference/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc),
[Language Team](https://github.com/rust-lang/lang-team/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc+) or
[Unsafe Code Guidelines](https://github.com/rust-lang/unsafe-code-guidelines/issues?q=is%3Aopen+label%3Afinal-comment-period+sort%3Aupdated-desc).*

Let us know if you would like your PRs, Tracking Issues or RFCs to be tracked as a part of this list.

#### [New and Updated RFCs](https://github.com/rust-lang/rfcs/pulls)
* [new] [RFC: `#[export_visibility = ...]` attribute.](https://github.com/rust-lang/rfcs/pull/3834)

## Upcoming Events

Rusty Events between 2025-06-18 - 2025-07-16 🦀

### Virtual
* 2025-06-18 | Virtual (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust/events/)
    * [**Rust Panics and FFI Boundaries**](https://www.meetup.com/vancouver-rust/events/307730493)
* 2025-06-19 | Hybrid (Redmond, WA, US) | [Seattle Rust User Group](https://www.meetup.com/join-srug)
    * [**June, 2025 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/seattle-rust-user-group/events/305658476)
* 2025-06-19 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/300820303)
* 2025-06-19 | Virtual (Girona, ES) | [Rust Girona](https://lu.ma/rust-girona)
    * [**Sessió setmanal de codificació / Weekly coding session**](https://lu.ma/vna66he1)
* 2025-06-22 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust)
    * [**Rust Readers Discord Discussion: Async Rust**](https://www.meetup.com/dallasrust/events/308246353)
* 2025-06-24 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust)
    * [**Fourth Tuesday**](https://www.meetup.com/dallasrust/events/305361436)
* 2025-06-24 | Virtual (London, UK) | [Women in Rust](https://www.meetup.com/women-in-rust)
    * [**Building Efficient Web Scrapers: Rust vs. Python for Data Ingestion**](https://www.meetup.com/women-in-rust/events/306683025)
* 2025-06-25 | Virtual (Lima, PE)| [Perú Rust User Group](https://www.meetup.com/peru-rust-user-group/)
    * [**Interfaces y Costos en la nube con Rust**](https://www.meetup.com/peru-rust-user-group/events/308543965/)
* 2025-06-26 | Virtual (Girona, ES) | [Rust Girona](https://lu.ma/rust-girona)
    * [**Sessió setmanal de codificació / Weekly coding session**](https://lu.ma/cgamfls6)
* 2025-06-26 | Virtual (Nürnberg, DE) | [Rust Nuremberg](https://www.meetup.com/rust-noris)
    * [**Rust Nürnberg online**](https://www.meetup.com/rust-noris/events/304567869)
* 2025-06-29 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust)
    * [**Rust Readers Discord Discussion: Async Rust**](https://www.meetup.com/dallasrust/events/kvqfrtyhcjbmc)
* 2025-07-02 | Virtual (Indianapolis, IN, US) | [Indy Rust](https://www.meetup.com/indyrs)
    * [**Indy.rs - with Social Distancing**](https://www.meetup.com/indyrs/events/302031667)
* 2025-07-03 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/300820304)
* 2025-07-03 | Virtual (Rotterdam, NL) | [Bevy Game Development](https://www.meetup.com/bevy-game-development/events/)
    * [**Bevy Meetup #11**](https://www.meetup.com/bevy-game-development/events/308463394)
* 2025-07-05 | Virtual (Kampala, UG) | [Rust Circle Meetup](https://www.eventbrite.com/o/rust-circle-kampala-65249289033)
    * [**Rust Circle Meetup**](https://www.eventbrite.com/e/rust-circle-meetup-tickets-628763176587)
* 2025-07-06 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Rust Readers Discord Discussion: Async Rust**](https://www.meetup.com/dallasrust/events/308298511)
* 2025-07-08 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Second Tuesday**](https://www.meetup.com/dallasrust/events/305361452)
* 2025-07-13 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Rust Readers Discord Discussion: Async Rust**](https://www.meetup.com/dallasrust/events/308298512)
* 2025-07-15 | Virtual (London, UK) | [Women in Rust](https://www.meetup.com/women-in-rust/events/)
    * [**👋 Community Catch Up**](https://www.meetup.com/women-in-rust/events/307560349)
* 2025-07-15 | Virtual (Washington, DC, US) | [Rust DC](https://www.meetup.com/rustdc/events/)
    * [**Mid-month Rustful**](https://www.meetup.com/rustdc/events/306757755)
* 2025-07-16 | Virtual (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust/events/)
    * [**Rust Study/Hack/Hang-out**](https://www.meetup.com/vancouver-rust/events/307731031)


### Asia
* 2025-06-28 | Bangalore/Bengaluru, IN | [Rust Bangalore](https://hasgeek.com/rustbangalore)
    * [**June 2025 Rustacean meetup**](https://hasgeek.com/rustbangalore/june-2025-rustacean-meetup/)
* 2025-07-02 | Seoul, KR | [Seoul Rust (Programming Language) Meetup](https://www.meetup.com/rust-seoul-meetup/events/)
    * [**Seoul Rust Meetup**](https://www.meetup.com/rust-seoul-meetup/events/308408246)

### Europe
* 2025-06-18 | Stockholm, SE | [Stockholm Rust](https://www.meetup.com/stockholm-rust)
    * [**Rust Meetup @Magello**](https://www.meetup.com/stockholm-rust/events/308129156)
* 2025-06-19 | Aarhus, DK | [Rust Aarhus](https://www.meetup.com/rust-aarhus)
    * [**Rust Aarhus meetup at Trifork**](https://www.meetup.com/rust-aarhus/events/308060489)
* 2025-06-19 | Edinburgh, UK | [Rust and Friends](https://www.meetup.com/rust-edi)
    * [**Rust and Friends (evening pub)**](https://www.meetup.com/rust-and-friends/events/308023524)
* 2025-06-20 | Edinburgh, UK | [Rust and Friends](https://www.meetup.com/rust-edi)
    * [**Rust and Friends (daytime coffee)**](https://www.meetup.com/rust-and-friends/events/308023512)
* 2025-06-23 | London, UK | [Rust London User Group](https://www.meetup.com/rust-london-user-group/events/)
    * [**Rust London: Rust Hack & Learn June 2025**](https://www.meetup.com/rust-london-user-group/events/308529202)
* 2025-06-24 | Manchester, UK | [Rust Manchester](https://www.meetup.com/rust-manchester)
    * [**Rust Manchester June Code Night**](https://www.meetup.com/rust-manchester/events/307919158)
* 2025-06-25 | London, UK | [London Rust Project Group](https://www.meetup.com/london-rust-project-group)
    * [**Lessons learnt from making a tiny game in nostd Rust**](https://www.meetup.com/london-rust-project-group/events/306809962)
* 2025-06-25 | Paris, FR | [Systematic Paris Region](https://systematic-paris-region.org/)   
    * [**Rust Paris Conference 2025**](https://my.weezevent.com/rust-paris-2025)
* 2025-06-26 | Barcelona, ES | [BcnRust](https://www.meetup.com/bcnrust/events/)
    * [**18th BcnRust Meetup**](https://www.meetup.com/bcnrust/events/308399403)
* 2025-06-26 | Copenhagen, DK | [Copenhagen Rust Community](https://www.meetup.com/copenhagen-rust-community)
    * [**Rust meetup #58**](https://www.meetup.com/copenhagen-rust-community/events/308161212)
* 2025-06-26 | Paris, FR | [Rust Paris](https://www.meetup.com/rust-paris/events/)
    * [**Rust meetup #77**](https://www.meetup.com/rust-paris/events/308416060)
* 2025-06-30 | Zagreb, HR | [impl Zagreb for Rust](https://www.meetup.com/zagreb-rust-meetup/events/)
    * [**Meetup 2025/06: Drink-up zatvaranje sezone**](https://www.meetup.com/zagreb-rust-meetup/events/308477879)
* 2025-07-01 | Gdansk, PL | [Rust Gdansk](https://www.meetup.com/rust-gdansk/events/)
    * [**Rust Gdansk Meetup #9**](https://www.meetup.com/rust-gdansk/events/308349712)
* 2025-07-02 | Basel, CH | [Rust Basel](https://www.meetup.com/rust-basel)
    * [**Rust Meetup #12 @ kHaus**](https://www.meetup.com/rust-basel/events/307567391)
* 2025-07-02 | London, UK | [Oxford Rust Meetup Group](https://www.meetup.com/oxford-rust-meetup-group/)
    * [**Oxford Rust and ACCU special - Vibe coding workshop**](https://www.meetup.com/oxford-rust-meetup-group/events/308435063/)
* 2025-07-02 | Posnan, PL | [Rust Poland](https://www.meetup.com/rust-poland-meetup/)
    * [**Rust Poland Meetup x Poznan**](https://www.meetup.com/rust-poland-meetup/events/308480357)
* 2025-07-05 | Stockholm, SE | [Stockholm Rust](https://www.meetup.com/stockholm-rust/events/)
    * [**Ferris' Fika Forum #13**](https://www.meetup.com/stockholm-rust/events/308530949)
* 2025-07-08 | London, UK | [London Rust Project Group](https://www.meetup.com/london-rust-project-group/events/)
    * [**Garbage Collection for Rust: the Finalizer Frontier**](https://www.meetup.com/london-rust-project-group/events/308443710)
* 2025-07-09 | Girona, ES | [Rust Girona](https://lu.ma/rust-girona)
    * [**Rust Girona Hack & Learn 07 2025**](https://lu.ma/hismn492)
* 2025-07-09 | Reading, UK | [Reading Rust Workshop](https://www.meetup.com/reading-rust-workshop/events/)
    * [**Reading Rust Meetup**](https://www.meetup.com/reading-rust-workshop/events/wrdkmtyhckbmb)
* 2025-07-15 | London, UK | [London Rust Project Group](https://www.meetup.com/london-rust-project-group/events/)
    * [**TUI Power: Simulating & Visualising Sensor Data with Rust**](https://www.meetup.com/london-rust-project-group/events/308434768)


### North America
* 2025-06-18 | Hybrid (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust)
    * [**Rust Study/Hack/Hang-out**](https://www.meetup.com/vancouver-rust/events/307730493)
* 2025-06-19 | Hybrid (Redmond, WA, US) | [Seattle Rust User Group](https://www.meetup.com/join-srug)
    * [**June, 2025 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/seattle-rust-user-group/events/305658476)
* 2025-06-19 | México City, MX | [Rust MX](https://www.meetup.com/rust-mx)
    * [**programación asíncrona en Rust usando Tokio**](https://www.meetup.com/rust-mx/events/308248260)
* 2025-06-19 | Nashville, TN, US | [Music City Rust Developers](https://www.meetup.com/music-city-rust-developers)
    * [**Using Rust For Web Series 3 : Final Presentations and Community Social**](https://www.meetup.com/music-city-rust-developers/events/304333108)
* 2025-06-19 | Redmond, WA, US | [Seattle Rust User Group](https://www.meetup.com/join-srug/events/)
    * [**June, 2025 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/seattle-rust-user-group/events/305658476)
* 2025-06-20 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust)
    * [**Lechmere Rust Lunch, June 20**](https://www.meetup.com/bostonrust/events/307936242)
* 2025-06-25 | Austin, TX, US | [Rust ATX](https://www.meetup.com/rust-atx)
    * [**Rust Lunch - Fareground**](https://www.meetup.com/rust-atx/events/xvkdgtyhcjbhc)
* 2025-06-26 | Los Angeles, CA, US | [Rust Los Angeles](https://www.meetup.com/rust-los-angeles/events/)
    * [**Rust in Web3 Developer Group**](https://www.meetup.com/rust-los-angeles/events/308401269)
* 2025-06-26 | Los Angeles (Chino Hills), CA, US | [Vara Network](https://lu.ma/events-by-vara-gear)
    * [**Rust in Web3**](https://lu.ma/ek8jx2r3)
* 2025-06-26 | Spokane, WA, US | [Spokane Rust](https://www.meetup.com/spokane-rust)
    * [**Monthly Meetup: Making a CRUD API with Rust!**](https://www.meetup.com/spokane-rust/events/307969600)
* 2025-06-28 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust)
    * [**Back Bay Rust Lunch, June 28**](https://www.meetup.com/bostonrust/events/307936269)
* 2025-07-03 | Montréal, QC, CA | [Rust Montréal](https://www.meetup.com/rust-montreal/events/)
    * [**July Monthly Social**](https://www.meetup.com/rust-montreal/events/308532058)
* 2025-07-03 | Saint Louis, MO, US | [STL Rust](https://www.meetup.com/stl-rust/events/)
    * [**Building Resilient and Observable Rust Services with steady_state**](https://www.meetup.com/stl-rust/events/306345853)
* 2025-07-06 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Alewife Rust Lunch, July 6**](https://www.meetup.com/bostonrust/events/307936287)
* 2025-07-09 | Phoenix, AZ, US | [Desert Rust](https://www.meetup.com/desert-rustaceans/events/)
    * [**Rust <> AI**](https://www.meetup.com/desert-rustaceans/events/308507249/)
* 2025-07-15 | San Francisco, CA, US | [San Francisco Rust Study Group](https://www.meetup.com/san-francisco-rust-study-group/events/)
    * [**Rust Hacking in Person**](https://www.meetup.com/san-francisco-rust-study-group/events/307931266)

### Oceania
* 2025-06-24 | Barton, AC, AU | [Canberra Rust User Group](https://www.meetup.com/rust-canberra/events/)
    * [**June Meetup**](https://www.meetup.com/rust-canberra/events/307520854)
* 2025-06-30 | Collingwood, VI, AU | [Rust Melbourne](https://www.meetup.com/rust-melbourne/events/)
    * [**June 2025 Mini Rust Melbourne Meetup**](https://www.meetup.com/rust-melbourne/events/308546374)

### South America
* 2025-07-12 | São Paulo, BR | [Rust São Paulo Meetup](https://www.meetup.com/rust-sao-paulo-meetup/events/)
    * [**Encontro do Rust-SP na WillBank**](https://www.meetup.com/rust-sao-paulo-meetup/events/307308851)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

## Jobs
<!--

Rust Jobs:

TWiR has stopped featuring individual job postings. You can read more about this change here:

https://github.com/rust-lang/this-week-in-rust/issues/3412

-->

Please see the latest [Who's Hiring thread on r/rust](https://www.reddit.com/r/rust/comments/1knkfb6/official_rrust_whos_hiring_thread_for_jobseekers/)

# Quote of the Week



> But after a few weeks, it compiled and the results surprised us. The code was 10x faster than our carefully tuned Kotlin implementation – despite no attempt to make it faster. To put this in perspective, we had spent years incrementally improving the Kotlin version from 2,000 to 3,000 transactions per second (TPS). The Rust version, written by Java developers who were new to the language, clocked 30,000 TPS.
>
> This was one of those moments that fundamentally shifts your thinking. Suddenly, the couple of weeks spent learning Rust no longer looked like a big deal, when compared with how long it’d have taken us to get the same results on the JVM. We stopped asking, “Should we be using Rust?” and started asking “Where else could Rust help us solve our problems?”

– [Dr. Werner Vogels on his blog](https://www.allthingsdistributed.com/2025/05/just-make-it-scale-an-aurora-dsql-story.html)

Thanks to [Brian Kung](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1697) for the suggestion!

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), [cdmistman](https://github.com/cdmistman), [ericseppanen](https://github.com/ericseppanen), [extrawurst](https://github.com/extrawurst), [U007D](https://github.com/U007D), [joelmarcey](https://github.com/joelmarcey), [mariannegoldin](https://github.com/mariannegoldin), [bennyvasquez](https://github.com/bennyvasquez), [bdillo](https://github.com/bdillo)*

*Email list hosting is sponsored by [The Rust Foundation](https://foundation.rust-lang.org/)*

<small>[Discuss on r/rust](https://this-week-in-rust.org/blog/2025/06/19/this-week-in-rust-604/)</small>
