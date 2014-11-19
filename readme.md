# Advanced Aria Templates snippets pack

A collection of sublime text editor snipptes for the [Aria Templates Framework](http://ariatemplates.com).

# Installation

## Sublime Package Control

Simply search for "Advanced Aria Templates snippets pack"

## Manual

Clone the repository inside your Sublime Text `Packages/User` folder (see `Preferences -> Browse Packages` for the correct path).

    git clone https://github.com/dpreussner/advanced-at-snippets-pack.git advanced-at-snippets-pack

# Available snipptes

Following snipptes are available:

## Template statements (.tpl)

See the [Aria Templates guide for writing templates](http://ariatemplates.com/usermanual/latest/writing_templates) for further reference on the basic template statements.

    call
    elseif
    for
    foreach
    id
    if
    ifelse
    macro
    repeater
    section
    set
    var
    view

## Aria Widgets Library (.tpl)

For every widget in the @aria Library there is a snippet which corresponds to the basic / most common configuration for the widget. See the [Aria Templates user manual page](http://ariatemplates.com/usermanual/latest/) or the [Aria Templates samples page](http://ariatemplates.com/samples/) for further reference on how to use widgets.

    // widgets
    autocomplete
    button
    calendar
    datefield
    datepicker
    dialog
    errorlist
    fieldset
    gauge
    iconbutton
    link
    list
    multiautocomplete
    multiselect
    numberfield
    passwordfield
    radiobutton
    splitter
    select
    selectbox
    sortindicator
    tab
    tabpanel
    template
    textarea
    text
    textfield
    timefield
    tooltip

    // widget config
    bind
    bindrefresh
    transform

## aria.utils.Array (.js)

    ariaArrayClone
    ariaArrayContains
    ariaArrayFilter
    ariaArrayForEach
    ariaArrayIndexOf
    ariaArrayIsEmpty
    ariaArrayRemove
    ariaArrayRemoveAt

## aria.utils.Type (.js)

    ariaTypeIsArray
    ariaTypeIsBoolean
    ariaTypeIsCallback
    ariaTypeIsContainer
    ariaTypeIsDate
    ariaTypeIsFunction
    ariaTypeIsHTMLElement
    ariaTypeIsNumber
    ariaTypeIsObject
    ariaTypeIsRegExp
    ariaTypeIsString

## aria.utils.Json (.js)

    ariaJsonAdd
    ariaJsonContains
    ariaJsonCopy
    ariaJsonEquals
    ariaJsonInject
    ariaJsonSetValue