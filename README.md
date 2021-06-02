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
                PHP::class,
                Javascript::class,
                Java::class,
            ],

            'frameworks' => [
                Laravel::class,
                VueJS::class,
                React::class,
            ],

            'devOps' => [
                AWS::class,
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

<a href = 'https://www.linkedin.com/in/samfelgar'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/linked-in-alt.svg"/></a>
<a href = 'https://www.twitter.com/samfelgar'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/twitter.svg"/></a>  <a href = 'https://www.github.com/samfelgar'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/github.svg"/></a> 

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
