<?php

namespace PhilipOwusuAfriyie;

class About{

    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'Getinnotized',
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Java::class,
            Django::class,
            Laravel::class,
            React::class,
            Node::class
        ];
    }
}
?>
