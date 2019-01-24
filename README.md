### Running test

```
./vendor/bin/phpunit
```

phpunut.xml

```
<env name="APP_ENV" value="testing"/>
<env name="APP_URL" value="http://127.0.0.1:8000"/>
<env name="DB_CONNECTION" value="sqlite"/>
<env name="DB_DATABASE" value=":memory:"/>
<env name="CACHE_DRIVER" value="array"/>
<env name="SESSION_DRIVER" value="array"/>
<env name="QUEUE_DRIVER" value="sync"/>
```

test class

```
use Illuminate\Foundation\Testing\DatabaseMigrations;


use DatabaseMigrations;
```
