![Header image](https://repository-images.githubusercontent.com/458058/af6a9d00-9374-11e9-887c-917673d9fe68)

The Symfony PHP framework.

### New contributors 🥰

 * @fliespl had their first pull request to symfony/symfony merged 🥇
 * @AndrolGenhald had their first pull request to symfony/symfony  merged 🥇
 * @topikito had **two** pull requests to symfony/symfony  merged 🥇🥇
 * @adamwojs had their first pull request to symfony/symfony  merged 🥇
 * @PedroTroller had their first pull request to symfony/symfony  merged 🥇

### Impactful contributors 

 * @Warxcell reported the most bugs that were fixed 🐛
 * @fabpot and @nikolas-grekas reviewed the most pull requests 👀
 * @nikolas-grekas had the most commits merged 📈 and added the most lines of code 🏋️‍♂️
 * @fabpot removed the most lines of code ✂️🔪🩸

### Changes <a href="https://github.com/symfony/symfony/compare/v5.2.5...v5.2.6">between v5.2.5...v5.2.6</a>

<details><summary><b>Security fixes</b></summary>

<br>

 * [Security] Use concrete UserInterface and UserProviderInterface classes in the tests #40609 by @wouterj (reviewed by @chalasr, @Nyholm)
 * [Security] Use more concrete user classes in tests #40612 by @wouterj (reviewed by @chalasr)
 * [Security] Handle properly 'auto' option for remember me cookie security #40537 by @fliespl (reviewed by @nicolas-grekas)
 * [Security] Refresh original user in SwitchUserListener #39992 by @AndrolGenhald (reviewed by @derrabus, @fabpot, @maxhelias, @OskarStark)

</details>

<details><summary><b>Bug fixes</b></summary>

<br>

 * [Form] error if the input string couldn't be parsed as a date #40598 by @xabbuh (reviewed by @fabpot, @kamil-jakubowski, @OskarStark)
 * [HttpClient] fix using stream_copy_to_stream() with responses cast to php streams #40587 by @nicolas-grekas (reviewed by @fabpot, @Nyholm)
 * [Form] IntegerType: Always use en for IntegerToLocalizedStringTransformer #40510 by @Warxcell (reviewed by @derrabus, @xabbuh, @yceruto)
 * Uses the correct assignment action for console options depending if they are short or long #40593 by @topikito (reviewed by @chalasr, @Nyholm)
 * [HttpKernel] ConfigDataCollector to return known data without the need of a Kernel #40535 by @topikito (reviewed by @derrabus, @fabpot, @nicolas-grekas, @Nyholm, @stof)
 * Fix Trying to clone an uncloneable object of class #40568 by @jderusse (reviewed by @nicolas-grekas)
 * [PhpUnitBridge] fix reported class when deprecated method is static #40558 by @xabbuh (reviewed by @nicolas-grekas)
 * [Translation] Fix update existing key with existing +int-icu domain #40552 by @axi (reviewed by @nicolas-grekas, @stof)
 * Fixed parsing deprecated definitions without message key #40541 by @adamwojs (reviewed by @nicolas-grekas)
 * [Validator] Avoid triggering the autoloader for user-input values #40506 by @Seldaek (reviewed by @nicolas-grekas, @Ocramius, @ro0NL, @stof)
 * Security Hardening - unserialize DumpDataCollector #40546 by @jderusse (reviewed by @nicolas-grekas)
 * [DependencyInjection] Fix return type of getSubscribedServices() #40423 by @derrabus (reviewed by @fabpot, @jderusse, @nicolas-grekas, @OskarStark, @stof)
 * Be explicit about anchor background color in profiler toolbar #40475 by @bezin (reviewed by @nicolas-grekas)
 * [Bridge\Twig] Add 'form-control-range' for range input type #40472 by @Oviglo (reviewed by @AngelFQC, @nicolas-grekas)
 * [ErrorHandler] Fix error caused by `include` + open_basedir #40242 by @stlrnz (reviewed by @nicolas-grekas)
 * [FrameworkBundle] Make the TestBrowserToken interchangeable with other tokens #40368 by @Seldaek (reviewed by @chalasr, @nicolas-grekas)
 * [Mailer] make async-ses required #40481 by @jderusse (reviewed by @fabpot)
 * [Mime] Escape commas in address names #39866 by @YaFou (reviewed by @Cartman34, @fabpot, @fbourigault, @maxhelias, @sstok)
 * Check if templating engine supports given view #40373 by @fritzmg (reviewed by @fabpot)
 * [Console] Fix type of InputOption::$default #40428 by @oliverklee (reviewed by @chalasr, @derrabus, @dmaicher, @jderusse)
 * [TwigBridge] Fix "Serialization of 'Closure'" error when rendering an TemplatedEmail #40446 by @jderusse (reviewed by @derrabus, @fabpot, @nicolas-grekas)
 * Fix `ConstraintViolation#getMessageTemplate()` to always return `string` #40416 by @Ocramius (reviewed by @derrabus, @fabpot, @xabbuh)
 * [DoctrineBridge] Fix eventListener initialization when eventSubscriber constructor dispatch an event #40425 by @jderusse (reviewed by @chalasr, @fabpot)
 * [FrameworkBundle] Fix PropertyAccess definition when not in debug #40313 by @PedroTroller (reviewed by @derrabus, @fabpot, @nicolas-grekas)
 * [Form] clear unchecked choice radio boxes even if clear missing is set to false #40417 by @xabbuh (reviewed by @fabpot, @yceruto)
 * [ErrorHandler] Added missing type annotations to FlattenException #40388 by @derrabus (reviewed by @fabpot, @stof, @yceruto)
 * [TwigBridge] Allow version 3 of the Twig extra packages #40407 by @derrabus (reviewed by @fabpot)

</details>

<details><summary><b>Everything Else</b></summary>

<br>

 * Release v5.2.6 #40617 by @fabpot (reviewed by @mary-doc)
 * [HttpKernel] fix docblock #40611 by @xabbuh (reviewed by @derrabus, @Nyholm, @OskarStark, @wouterj)
 * [Filesystem] Fix dumpFile() method call #40608 by @sebpacz (reviewed by @Nyholm, @xabbuh)
 * [Form] skip intl dependent tests if the extension is missing #40606 by @xabbuh
 * [VarDumper] make DateCaster tests timezone-agnostic #40599 by @xabbuh (reviewed by @Nyholm)
 * [travis] remove cache of composer.lock for deps=low #40559 by @nicolas-grekas
 * [Filesystem] Fix comment with typo #40560 by @sebpacz (reviewed by @nicolas-grekas)
 * [travis] use packagist API v2 #40557 by @nicolas-grekas
 * [Contracts] Fix branch name in README.md links #40553 by @chalasr (reviewed by @nicolas-grekas)
 * [HttpClient] remove using $http_response_header #40538 by @nicolas-grekas (reviewed by @fabpot, @jderusse, @stof)
 * [Translation] fix test case name #40470 by @nicolas-grekas (reviewed by @chalasr)
 * [4.4] Fix wrong namespace in tests #40464 by @chalasr (reviewed by @derrabus)
 * [RateLimiter] [5.2] Fix wrong namespace in tests #40465 by @chalasr (reviewed by @derrabus)
 * [Routing] Remove unnecessary references to User class in test fixtures #40463 by @chalasr (reviewed by @derrabus)
 * [Mailer] fix lowest allowed dependencies #40455 by @xabbuh (reviewed by @Nyholm)
 * Update translations for Norwegian Nynorsk (nn) #38756 #40435 by @glye (reviewed by @fabpot, @Nyholm)

</details>
