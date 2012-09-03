yii.ext.gplacesautocomplete
===========================

Yii extension for wrapping Google Places Autocomplete (https://developers.google.com/maps/documentation/javascript/places#places_autocomplete) as an input widget.
See the screenshot.

Requirement
-----------
This widget is tested with Yii 1.1.10.


Usage
-----
To use this widget just put the `gplacesautocomplete` directory to `extensions` directory and then put the code below.

    $this->widget('ext.gplacesautocomplete.GPlacesAutoComplete', array(
        'name' => 'city',
        'options' => array(
            'types' => array(
                '(cities)'
            ),
            'componentRestrictions' => array(
                'country' => 'us',
            )
        )
    ));

Changelog
---------
* 2012-09-03 Created the initial version.

