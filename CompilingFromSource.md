  1. _(Optional)_ If you don't have it already, grab the [Flex SDK](http://opensource.adobe.com/wiki/display/flexsdk/Flex+SDK) and extract it.
  1. Grab libas3zip from http://libas3zip.googlecode.com/svn/trunk/.
  1. _(Optional)_ Edit the configuration/flex-config.xml file to fit your needs.
  1. Open up a terminal screen, go to the directory libas3zip is in.
  1. Execute compc like this _Flex SDK directory_`/bin/compc -load-config configuration/flex-config.xml -external-library-path+=`_Flex SDK directory_`/frameworks/libs/player/10/playerglobal.swc`.