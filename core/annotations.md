# Annotations

## @ApiResource

*Since 2.0.0*

Est l'annotation que l'on utilise sur une entité pour qu'API Platform puisse connaitre la ressource à exposer.

### Default configuration

```php
<?php
// api/src/Entity/Book.php

use ApiPlatform\Core\Annotation\ApiResource;

/**
 * @ApiResource
 */
class Book
{
    // ...
}
```

Ce qui correspond à ceci :

```php
<?php
// api/src/Entity/Book.php

use ApiPlatform\Core\Annotation\ApiResource;

/**
 * @ApiResource
 */
class Book
{
    // ...
}
```

### Full configuration

```php
<?php
// api/src/Entity/Book.php

use ApiPlatform\Core\Annotation\ApiResource;

/**
 * @ApiResource
 */
class Book
{
    // ...
}
```

### Attribute shortName
### Attribute description
### Attribute iri
### Attribute itemOperations
### Attribute collectionOperations
### Attribute subresourceOperations
### Attribute graphql
### Attribute attributes

## @ApiFilter

## @ApiProperty

## @ApiSubresource
