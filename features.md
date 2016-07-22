#Features

- Preserver should provide a trait that uses a required protected variable $recipe that is an array that maps the properties of the object.
- Preserver should be able to write and retrieve an object from a file or database.
- Preserver should be able to take an object that does not use the trait with a map for the data properties, this option may be limited to public properties.
- Preserver ideally should be able to use the recipe/map to map properties and/or methods to set and retrieve properties from an object for storage and retrieval.
- Preserver saves objects as jam file or db entry.
- Preserver's jam syntax is json with required fields of class, recipe key or array, and data.
- Preserver should include optional hooks for a laravel project including registering config, service provider, facade and use Eloquent for tracking its jam files.
- Preserver should be able to be given a jam file or entry and return the appropriate object.
- Preserver should be able by a fromDir function retrieve all jam's from a dir.
- Preserver should be able by a fromTable function retrieve all jam's from a db table.
- Preserver will require a db or file for tracking the jam's, configurable by the config file, default is db table.
- Preserver should throw an exception if it cannot preserver or retrieve an object for any reason.