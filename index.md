# PHP Standard Recommendations

According to the [PSR Workflow Bylaw][workflow] each PSR has a status as it is being worked on. Once a proposal has passed the Entrance Vote it will be listed here as "Draft". Unless a PSR is marked as "Accepted" it is subject to change. Draft can change drastically, but Review will only have minor changes.

As also described in the [PSR Workflow Bylaw][workflow]. The Editor, or editors, of a proposal are the essentially the lead contributors and writers of the PSRs and they are supported by two voting members. Those voting members are the Coordinator who is responsible for managing the review stage and votes; and a second sponsor.

## Index by Status

### Accepted

| Num | Title                          | Editor                         |  Coordinator            | Sponsor          |
|:---:|--------------------------------|--------------------------------|-------------------------|------------------|
| 1   | [Basic Coding Standard][psr1]  | Paul M. Jones                  | _N/A_                   | _N/A_            |
| 2   | [Coding Style Guide][psr2]     | Paul M. Jones                  | _N/A_                   | _N/A_            |
| 3   | [Logger Interface][psr3]       | Jordi Boggiano                 | _N/A_                   | _N/A_            |
| 4   | [Autoloading Standard][psr4]   | Paul M. Jones                  | Phil Sturgeon           | Larry Garfield   |
| 6   | [Caching Interface][psr6]      | Larry Garfield                 | Paul Dragoonis          | Robert Hafner    |
| 7   | [HTTP Message Interface][psr7] | Matthew Weier O'Phinney        | Beau Simensen           | Paul M. Jones    |
| 11  | [Container Interface][psr11]   | Matthieu Napoli, David Négrier | Matthew Weier O'Phinney | Korvin Szanto    |
| 13  | [Hypermedia Links][psr13]      | Larry Garfield                 | Matthew Weier O'Phinney | Marc Alexander   |
| 15  | [HTTP Handlers][psr15]         | Woody Gilk                     | _N/A_                   | Matthew Weier O'Phinney |
| 16  | [Simple Cache][psr16]          | Paul Dragoonis                 | Jordi Boggiano          | Fabien Potencier |
| 17  | [HTTP Factories][psr17]        | Woody Gilk                     | _N/A_                   | Matthew Weier O'Phinney |

### Review

| Num | Title                                | Editor(s)                      |
|:---:|--------------------------------------|--------------------------------|
| 18  | [HTTP Client][psr18]                 | Tobias Nyholm                  |

### Draft

| Num | Title                                | Editor(s)                      |
|:---:|--------------------------------------|--------------------------------|
| 5   | [PHPDoc Standard][psr5]              | Chuck Burgess                  |
| 12  | [Extended Coding Style Guide][psr12] | Korvin Szanto                  |
| 14  | [Event Manager][psr14]               | Larry Garfield                 |
| 19  | [PHPDoc tags][psr19]                 | Chuck Burgess                  |

### Abandoned

| Num | Title                                | Editor(s)                      |
|:---:|--------------------------------------|--------------------------------|
| 8   | [Huggable Interface][psr8]           | Larry Garfield                 |
| 9   | [Security Advisories][psr9]          | Michael Hess                   |
| 10  | [Security Reporting Process][psr10]  | Michael Hess                   |

### Deprecated

| Num | Title                          | Editor                  |
|:---:|--------------------------------|-------------------------|
| 0   | [Autoloading Standard][psr0]   | Matthew Weier O'Phinney |

## Numerical Index

| Num | Title                                | Editor(s)                      | Status     |
|:---:|--------------------------------------|--------------------------------|------------|
| 0   | [Autoloading Standard][psr0]         | Matthew Weier O'Phinney        | Deprecated |
| 1   | [Basic Coding Standard][psr1]        | Paul M. Jones                  | Accepted   |
| 2   | [Coding Style Guide][psr2]           | Paul M. Jones                  | Accepted   |
| 3   | [Logger Interface][psr3]             | Jordi Boggiano                 | Accepted   |
| 4   | [Autoloading Standard][psr4]         | Paul M. Jones                  | Accepted   |
| 5   | [PHPDoc Standard][psr5]              | Chuck Burgess                  | Draft      |
| 6   | [Caching Interface][psr6]            | Larry Garfield                 | Accepted   |
| 7   | [HTTP Message Interface][psr7]       | Matthew Weier O'Phinney        | Accepted   |
| 8   | [Huggable Interface][psr8]           | Larry Garfield                 | Abandoned  |
| 9   | [Security Advisories][psr9]          | Michael Hess                   | Abandoned  |
| 10  | [Security Reporting Process][psr10]  | Michael Hess                   | Abandoned  |
| 11  | [Container Interface][psr11]         | Matthieu Napoli, David Négrier | Accepted   |
| 12  | [Extended Coding Style Guide][psr12] | Korvin Szanto                  | Draft      |
| 13  | [Hypermedia Links][psr13]            | Larry Garfield                 | Accepted   |
| 14  | [Event Manager][psr14]               | Larry Garfield                 | Draft      |
| 15  | [HTTP Handlers][psr15]               | Woody Gilk                     | Accepted   |
| 16  | [Simple Cache][psr16]                | Paul Dragoonis                 | Accepted   |
| 17  | [HTTP Factories][psr17]              | Woody Gilk                     | Accepted   |
| 18  | [HTTP Client][psr18]                 | Tobias Nyholm                  | Review     |
| 19  | [PHPDoc tags][psr19]                 | Chuck Burgess                  | Draft      |

[workflow]: https://github.com/php-fig/fig-standards/blob/master/bylaws/002-psr-workflow.md
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-000.md
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-001-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-002-coding-style-guide.md
[psr3]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-003-logger-interface.md
[psr4]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-004-autoloader-meta.md
[psr5]: https://github.com/phpDocumentor/fig-standards/tree/master/proposed/phpdoc.md
[psr6]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-006-cache.md
[psr7]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-007-http-message.md
[psr8]: https://github.com/php-fig/fig-standards/blob/master/proposed/psr-8-hug/
[psr9]: https://github.com/php-fig/fig-standards/blob/master/proposed/security-disclosure-publication.md
[psr10]: https://github.com/php-fig/fig-standards/blob/master/proposed/security-reporting-process.md
[psr11]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-011-container.md
[psr12]: https://github.com/php-fig/fig-standards/blob/master/proposed/extended-coding-style-guide.md
[psr13]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-013-links.md
[psr14]: https://github.com/php-fig/fig-standards/blob/master/proposed/event-dispatcher.md
[psr15]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-015-request-handlers.md
[psr16]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-016-simple-cache.md
[psr17]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-017-http-factory.md
[psr18]: https://github.com/php-fig/fig-standards/tree/master/proposed/http-client/
[psr19]: https://github.com/php-fig/fig-standards/blob/master/proposed/phpdoc-tags.md
