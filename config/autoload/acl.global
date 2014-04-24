<?php

return array(
    'bjyauthorize' => array(
        'guards' => array(
            'BjyAuthorize\Guard\Controller' => array(
                array(
                    'controller' => 'zfcuser',
                    'action' => array('index', 'logout'),
                    'roles' => array('user', 'admin', 'guest')
                ),
                array(
                    'controller' => 'zfcuser',
                    'action' => array('login'),
                    'roles' => array('guest')
                )
            ),
            'BjyAuthorize\Guard\Route' => array(
                array('route' => 'zfcuser', 'roles' => array('user', 'admin')),
                array('route' => 'zfcuser/logout', 'roles' => array('user', 'admin', 'guest')),
                array('route' => 'zfcuser/login', 'roles' => array('guest')),
                array('route' => 'home', 'roles' => array('user', 'admin')),
                array('route' => 'user', 'roles' => array('user', 'admin')),
                array('route' => 'base', 'roles' => array('user', 'admin', 'guest')),
                array('route' => 'base/wildcard', 'roles' => array('user', 'admin', 'guest')),
            )
        )
    )
);