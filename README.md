Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to You under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## [Data files Bundles for CMU-Sphinx](https://github.com/sumansaurabh/Sphinx-Model)

This source repository only holds the pom.xml file and folder structure of this bundle.

To avoid loading subversion repository with large binary files this artifact has to be build and deployed manually to retrieve precomputed models from other sites.


## Downloading the CMU-Sphinx acoustic, language and dictionary model 

#Default Location:
1) [Acoustic](http://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/US%20English%20Generic%20Acoustic%20Model/en-us.tar.gz/download) en-us genric Acosutic Model is used for better performance

2) [Dictionary](https://svn.code.sf.net/p/cmusphinx/code/trunk/sphinx4/sphinx4- data/src/main/resources/edu/cmu/sphinx/models/acoustic/wsj/dict/cmudict.0.6d) cmudict.0.6d

3) [Language](https://svn.code.sf.net/p/cmusphinx/code/trunk/sphinx4/sphinx4-data/src/main/resources/edu/cmu/sphinx/models/language/en-us.lm.dmp) en-us.lm.dmp


For fast download of model files, model files has been [downloaded](https://sphinx-model.googlecode.com/svn/trunk) from here and not from above If you are security conscious, please change the download link. There will need some minor changes to POM file too.

## NOTE  

Using this bundles is only an alternative of manually copying the required Sphinx models to the '{stanbol-installation}/sling/datafiles'.

In addition model files in this folder have precedence to models provided by this bundle.




