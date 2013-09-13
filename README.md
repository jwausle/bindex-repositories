bindex-repositories
===================

is a collection of bindex.(xml/xml.gz) repositories ready to use as bnd-repository.

## HOWTO bnd

- open ${bnd.cnf-project}/ext/repository.xml
- append to 'plugin' property

```no-highlight
plugin: \
 aQute.bnd.deployer.repository.FixedIndexedRepo; name=Log4j2-dependency-repository; locations=https://github.com/jwausle/bindex-repositories/raw/master/log4j2-dependency-repository.xml
```
 
## LINKS
- bnd: http://www.aqute.biz/Code/Bnd
- bndindex: http://www.osgi.org/Repository/BIndex

