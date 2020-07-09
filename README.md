```php
<?php

namespace CaioNorder;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => '**********',
                'position' => 'Software Engineer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            CakePHP::class,
            NodeJs::class,            
            DenoJS::class,
            Angular::class,
            ReactNative::class,
            DigitalOcean::class,
            Aws::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```