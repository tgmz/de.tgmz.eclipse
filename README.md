<!--
/*******************************************************************************
  * Copyright (c) 10.03.2022 Thomas Zierer.
  * All rights reserved. This program and the accompanying materials
  * are made available under the terms of the Eclipse Public License v2.0
  * which accompanies this distribution, and is available at
  * http://www.eclipse.org/legal/epl-v20.html
  *
  * Contributors:
  *    Thomas Zierer - initial API and implementation and/or initial documentation
  *******************************************************************************/
-->

# My Eclipse

This is a sample for building a personalized Eclipse-IDE. 

## Adopt
To adopt, simply edit the target, product and config.ini files

## Build
Run `mvn verify -Pmaterialize` and unzip de.tgmz.eclipse.product\target\products\eclipse-win32.win32.x86_64.zip
 
Configure other platforms in pom.xml (parent & product)

## Included Plugins
*   Base: Eclipse 2023-09 
*   JEE, Web Developer Tools
*	CVS Client
*	Maven (m2e)
*   Buildship (Gradle)
*	Git
*	ECD: Enhanced Class Decompiler
*   DBeaver
