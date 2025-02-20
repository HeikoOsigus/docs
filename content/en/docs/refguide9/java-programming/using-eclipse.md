---
title: "Using Eclipse"
url: /refguide9/using-eclipse/
weight: 2

description: "Describes how to set up Eclipse, and how to add a Mendix application to Eclipse and launch it."
tags: ["studio pro"]
---

## 1 Introduction

You can use Eclipse to write and debug Java actions in your Mendix app. When the Mendix model is deployed, an Eclipse project file, classpath file, and launch configuration are generated.

## 2 Setting Up Eclipse

In Mendix, all text is saved in UTF-8 encoding. To make sure your source code is also saved in UTF-8, do the following:

1. Select **Window > Preferences**.
2. Select **Workspace** in the new menu window.
3. Select **UTF-8**:

    {{< figure src="/attachments/refguide9/java-programming/using-eclipse/eclipse-utf8-encoding.png" alt="Settings UTF-8 encoding" class="no-border" >}}

You should also have a Java Development Kit (JDK) installed and selected.

{{< figure src="/attachments/refguide9/java-programming/using-eclipse/eclipse-jdk.png" alt="Selecting a default JDK" class="no-border" >}}

Make sure to add a JDK and select it as the default in Eclipse.

## 3 Adding a Mendix App

To add a Mendix app to Eclipse, do the following:

1. Select **File > Import**.
2. Open the **General** folder, select **Existing Projects into Workspace** and select **Next >**:

    {{< figure src="/attachments/refguide9/java-programming/using-eclipse/eclipse-select-import.png" alt="Import existing project" class="no-border" >}}

3. Use the option **Select root directory**, browse to your Mendix app folder and select **Finish**:

    {{< figure src="/attachments/refguide9/java-programming/using-eclipse/import-eclipse-project.png" alt="Select root directory" class="no-border" >}}

## 4 Launching a Mendix App

To launch the app, do the following:

1. Select **Run > Run configurations...** or **Run > Debug configurations...**, depending on how you would like to start the application. 
2. Select **Java application** and a launch configuration—generated by Mendix Studio Pro—will appear.
3. Select **Run** (or **Debug**) to start the application:

    {{< figure src="/attachments/refguide9/java-programming/using-eclipse/eclipse-run-configuration.png" alt="Launch configuration" class="no-border" >}}

After you have launched the application, the **M2EE Admin Console** will appear. This is the same console as you would normally see in Mendix Studio Pro, if you would run the application from there. You can stop your application by closing the console.

{{< figure src="/attachments/refguide9/java-programming/using-eclipse/eclipse-debug-log.png" alt="M2EE Admin Console" class="no-border" >}}
