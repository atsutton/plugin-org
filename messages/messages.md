# HelpDefaults

If not supplied, the apiversion, template, and outputdir use default values.

# HelpOutputDirRelative

The outputdir can be an absolute path or relative to the current working directory.

# HelpOutputDirRelativeLightning

If you don’t specify an outputdir, we create a subfolder in your current working directory with the name of your bundle. For example, if the current working directory is force-app and your Lightning bundle is called myBundle, we create force-app/myBundle/ to store the files in the bundle.

# HelpExamplesTitle

Examples:

# OutputDirFlagDescription

folder for saving the created files

# OutputDirFlagLongDescription

The directory to store the newly created files. The location can be an absolute path or relative to the current working directory. The default is the current directory.

# TemplateFlagDescription

template to use for file creation

# TemplateFlagLongDescription

The template to use to create the file. Supplied parameter values or default values are filled into a copy of the template.

# TargetDirOutput

target dir = %s

# App

app

# Event

event

# Interface

interface

# Test

test

# Component

component

# Page

page

# AlphaNumericNameError

Name must contain only alphanumeric characters.

# NameMustStartWithLetterError

Name must start with a letter.

# EndWithUnderscoreError

Name can't end with an underscore.

# DoubleUnderscoreError

Name can't contain 2 consecutive underscores.

# SecurityWarning

This command will expose sensitive information that allows for subsequent activity using your current authenticated session.
Sharing this information is equivalent to logging someone in under the current credential, resulting in unintended access and escalation of privilege.
For additional information, please review the authorization section of the https://developer.salesforce.com/docs/atlas.en-us.234.0.sfdx_dev.meta/sfdx_dev/sfdx_dev_auth_web_flow.htm