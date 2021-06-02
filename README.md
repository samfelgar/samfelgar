```php
<?php

namespace Samuel;

class About extends Me
{
    public function __construct()
    {
        echo 'Hi there!';
    }

    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'mLearn',
                'position' => 'Backend developer'         
            ]
        ];
    }

    public function getKnowledge(): array
    {
        return [
            'programmingLanguages' => [
                Php::class,
                Javascript::class,
                Java::class,
            ],

            'frameworks' => [
                Laravel::class,
                Vuejs::class,
                React::class,
            ],

            'devOps' => [
                Aws::class,
                Docker::class,
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To learn, always';
    }
}

```


<center>

### [@samfelgar](https://twitter.com/samfelgar)

### [linkedin](https://www.linkedin.com/in/samfelgar/)

</center>

<!--
**samfelgar/samfelgar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
