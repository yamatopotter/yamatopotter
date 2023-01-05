```php
<?php
namespace Matheus Barreto;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'None. Wanna hire me?',
                'position' => 'Freelancer'         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            React::class,
            Bootstrap::class,
            Aws::class,
        ];
    }
    public function getFutureGoal(): string
    {
        return 'To contribute to open source projects.';
    }
}
```
