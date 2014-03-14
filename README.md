Maven Dependency Blocks
============

I use the blocks to group up common sets of dependencies for projects. A block can be used by including a dependency to 
your project like this

~~~
<dependency>
	<groupId>dex.blocks</groupId>
	<artifactId>test</artifactId>
	<type>pom</type>
	<scope>test</scope>
</dependency>
~~~
The blocks can be used to filter out problematic dependencies once rather than dealing with the same problems again and again.
THe most useful blocks are the test block, to add JUnit, Mockito and EasyMock and lang for adding Guava, Joda-Time, Slf4j, commons-lang and commons-collections.