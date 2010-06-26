# Wads_Config_Yaml

Zend_Auth_Storage extension using Cookie

# Usage

```php
require_once 'Wads/Auth/Storage/Cookie.php';

// Save reference of Zend_Auth
$auth = Zend_Auth::getInstance();

// Use Wads_Auth_Strage_Cookie as Zend_Auth_Strage
$auth->setStorage(new Wads_Auth_Storage_Cookie('my_name'));
```
