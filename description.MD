Test for impex:

```csv

UPDATE Customer[batchmode = true]; itemtype(code)[unique = true]; sessionLanguage(isocode);
                                 ; Customer                     ; en                      ;
								 
```
Test for xml:
```xml
<configuration xmlns="hybris.de/schemas/hmc/generic"
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xsi:schemaLocation="hybris.de/schemas/hmc/generic hmc.xsd">

    <explorertree>
        <group name="pricesettings" mode="delete"/>
        <group name="c2l" mode="delete"/>
        <group name="catalog" mode="delete"/>
    </explorertree>

</configuration>
```