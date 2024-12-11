[<img alt="Super Mario Gif" width="100%" src="https://user-images.githubusercontent.com/70382532/138322189-2db8df52-9dcb-40a0-88a8-c365466bd33d.gif">](https://github.com/babisobrinho)
Art by <a href="https://www.instagram.com/pixeljeff_design">@pixeljeff_design</a>

##
<br/>

```php
<?php

namespace babiSobrinho;

class About extends Me
{
    public function getCurrentSituation(): array
    {
        return [
            'openToWork' => [
              'type' => 'Freelancing',
              'position' => 'Full-stack Web Developer'       
            ]
        ];
    }

    public function getEducation(): array
    {
        return [
            'university' => [
                'name' => 'Instituto Politécnico de Leiria',
                'course' => 'Web Development & Multimedia'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            TailwindCss::class,
            Bootstrap::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

<!-- Contact Links -->
[<img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=E64DA1" target="_blank"/>](https://www.linkedin.com/in/babisobrinho)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/babisobrinho/babisobrinho/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/babisobrinho/babisobrinho/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/babisobrinho/babisobrinho/output/github-contribution-grid-snake.svg">
</picture>

![Visitor Count](https://profile-counter.glitch.me/{babisobrinho}/count.svg)
