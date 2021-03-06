yii2-widgets
============

This extension enhances or adds functionality to existing Yii Framework 2 Widgets to make available other bundled features available in Twitter Bootstrap 3.0, new HTML 5 features and affiliated Bootstrap extras. The widgets currently available are:

### Forms/Inputs

#### ActiveForm
[```VIEW DEMO```](http://demos.krajee.com/widget-details/active-form)  

Extends [Yii ActiveForm widget](https://github.com/yiisoft/yii2/blob/master/framework/widgets/ActiveForm.php). Facilitates all [three form layouts](http://getbootstrap.com/css/#forms-example) available in Bootstrap i.e. __vertical__, __horizontal__, and __inline__. Allows options for offsetting labels and inputs for horizontal form layout. Works closely with the extended ActiveField widget.
	
#### ActiveField
[```VIEW DEMO```](http://demos.krajee.com/widget-details/active-field)

Extends [Yii ActiveField widget](https://github.com/yiisoft/yii2/blob/master/framework/widgets/ActiveField.php). Allows Bootstrap styled [input group addons](http://getbootstrap.com/components/#input-groups-basic) to be prepended or appended to textInputs. Automatically adjusts checkboxes and radio input offsets for horizontal forms. Allows, flexibility to control the labels and placeholders based on form layout style (e.g. hide labels and show them as placeholder for inline forms). The extended ActiveField functionalities available are:

- Addons
	* Prepend Addon
	* Append Addon
	* Icon Addon
	* Input Addon
	* Button Addon
	* Button Dropdown Addon
	* Segmented Button Addon
	* Prepend & Append
	* Input Group Settings
- Inputs
	* Checkbox
	* Radio
	* Checkbox List
	* Radio List
	* Static Input
	* HTML 5 Input
- Multi Select
	* Vertical Form
	* Horizontal Form
	* Radio List
	* Display Options

#### Select2
[```VIEW DEMO```](http://demos.krajee.com/widget-details/select2)  

The Select2 widget is a Yii 2 wrapper for the [Select2 jQuery plugin](http://ivaynberg.github.io/select2/). 
This input widget is a jQuery based replacement for select boxes. It supports searching, remote data sets, 
and infinite scrolling of results. The widget is specially styled for Twitter Bootstrap 3. The widget allows
graceful degradation to a normal HTML select or text input, if the browser does not support JQuery.

#### Typeahead
[```VIEW DEMO```](http://demos.krajee.com/widget-details/typeahead)

The Typeahead widget is a Yii 2 wrapper for for the [Twitter Typeahead.js](http://twitter.github.com/typeahead.js/examples) 
plugin with certain custom enhancements. This input widget is a jQuery based replacement for text inputs providing search and 
typeahead functionality. It is inspired by twitter.com's autocomplete search functionality and based on Twitter's `typeahead.js` 
which is described as as a fast and fully-featured autocomplete library. The widget is specially styled for Twitter Bootstrap 3. 
The widget allows graceful degradation to a normal HTML text input, if the browser does not support JQuery. You can setup model 
validation rules for a model attribute that uses Typeahead widget for input like any other field.

#### DatePicker
[```VIEW DEMO```](http://demos.krajee.com/widget-details/datepicker)  

The DatePicker widget is a Yii 2 wrapper for the [Bootstrap DatePicker plugin](http://eternicode.github.io/bootstrap-datepicker/). 
The plugin is a fork of Stefan Petre's DatePicker (of eyecon.ro), with improvements by @eternicode. This widget is specially 
styled for Yii framework 2.0 and Twitter Bootstrap 3. The widget allows graceful degradation to a normal HTML text input, if 
the browser does not support JQuery.  This widget supports these markups:

* Simple Input Markup
* Component Markup - Addon Prepended
* Component Markup - Addon Appended
* Date Range Markup (from and to dates)
* Inline / Embedded Markup

#### TimePicker
[```VIEW DEMO```](http://demos.krajee.com/widget-details/timepicker)  

The TimePicker widget  allows you to easily select a time for a text input using your mouse or keyboards arrow keys. The widget is a
wrapper enhancement of the <a href='https://github.com/rendom/bootstrap-3-timepicker' target='_blank'>TimePicker plugin</a> by rendom 
forked from  <a href='https://github.com/jdewit/bootstrap-timepicker' target='_blank'>jdewit's TimePicker</a>. This widget as used 
here has been specially enhanced for Yii framework 2.0 and Twitter Bootstrap 3.

#### TouchSpin
[```VIEW DEMO```](http://demos.krajee.com/widget-details/touchspin)  

The TouchSpin widget is a Yii 2 wrapper for for the [bootstrap-touchspin](http://www.virtuosoft.eu/code/bootstrap-touchspin/) plugin by István Ujj-Mészáros, with certain additional enhancements. This input widget is a mobile and touch friendly input spinner component for Twitter Bootstrap 3. You can use the widget buttons to rapidly increase and decrease numeric and/or decimal values in your input field. The widget can be setup to include model validation rules for the related model attribute. 

#### FileInput
[```VIEW DEMO```](http://demos.krajee.com/widget-details/fileinput)  

The FileInput widget is a customized file input widget based on HTML5 file input. The widget enhances the default HTML file input with various features including the following:

* Specially styled for Twitter Bootstrap 3.0 with customizable buttons, caption, and preview
* Ability to select and preview multiple files
* Includes file browse and optional remove and upload buttons.
* Ability to format your file picker button styles
* Ability to preview files before upload - images and/or text (uses HTML5 FileReader API)
* Ability to preview multiple files of different types (both images and text)
* Set your upload action/route (defaults to form submit). Customize the Upload and Remove buttons.
* Internationalization enabled for easy translation to various languages

#### ColorInput
[```VIEW DEMO```](http://demos.krajee.com/widget-details/colorinput)  

The ColorInput widget is a customized color input widget based on HTML5 color input. The widget enhances the default HTML range input with various features including the following:

* Specially styled for Twitter Bootstrap 3.0 with customizable caption showing the output of the control.
* Ability to prepend and append addons.
* Allow the input to be changed both via the control or the text box.
* Automatically degrade to normal text input for unsupported Internet Explorer versions.

#### RangeInput
[```VIEW DEMO```](http://demos.krajee.com/widget-details/rangeinput)  

The RangeInput widget is a customized range slider control widget based on HTML5 range input. The widget enhances the default HTML range input with various features including the following:

* Specially styled for Twitter Bootstrap 3.0 with customizable caption showing the output of the control.
* Ability to prepend and append addons (very useful to show the min and max ranges, and the slider measurement unit).
* Allow the input to be changed both via the control or the text box.
* Automatically degrade to normal text input for unsupported Internet Explorer versions.

##### Future planned enhancements:

* Drag and drop functionality
* Realign/Rearrange the items in preview window
* Better captioning for each file in the preview window
* Support for previewing content other than image and text (e.g. HTML)

The widget runs on all modern browsers supporting HTML5 File Inputs and File Processing API. For browser versions IE9 and below, this widget will gracefully degrade to normal HTML file input. The widget is vastly inspired by this [blog article](http://www.abeautifulsite.net/blog/2013/08/whipping-file-inputs-into-shape-with-bootstrap-3/) and [Jasny's File Input plugin](http://jasny.github.io/bootstrap/javascript/#fileinput).
 
### Navigation

#### Affix
[```VIEW DEMO```](http://demos.krajee.com/affix-demo)  

Extends [Yii Menu widget](https://github.com/yiisoft/yii2/blob/master/framework/widgets/Menu.php). This widget offers a [scrollspy](http://getbootstrap.com/javascript/#scrollspy) and [affixed](http://getbootstrap.com/javascript/#affix) enhanced navigation (upto 2-levels) to highlight sections and secondary sections in each page. The affix widget can be used to generate both the:

- **Sidebar Menu:** Displays the scrollspy/affix navigation menu as a sidebar, and/or
- **Main Body:** Displays the main body sections based on the section & subsection headings and content passed.

The parameters to pass are:

- `type` The affix content type. Must be either `menu` or `body`. Defaults to `menu`
- `items`: The affix content items as an array. Check the [affix combined usage](http://demos.krajee.com/widget-details/affix#affix-menu-body) for a detailed example.

> **Note:**
> If you have the `header` section fixed to the top, you must add a CSS class `kv-header` to the header container. Similarly, for a fixed footer you must add the class `kv-footer` to your footer container. This will ensure a correct positioning of the affix widget on the page.


#### SideNav
[```VIEW DEMO```](http://demos.krajee.com/sidenav-demo/profile/default)  

This widget is a collapsible side navigation menu built to seamlessly work with Twitter Bootstrap framework. It is built over Twitter Bootstrap [stacked nav](http://getbootstrap.com/components/#nav-pills) component. This widget class extends the [Yii Menu widget](https://github.com/yiisoft/yii2/blob/master/framework/widgets/Menu.php). Upto 3 levels of submenus are by default supported by the CSS styles to balance performance and useability. You can choose to extend it to more or less levels by customizing the [CSS](https://github.com/kartik-v/yii2-widgets/blob/master/assets/css/sidenav.css).

### Demo
You can see a [demonstration here](http://demos.krajee.com/widgets) on usage of these widgets with documentation and examples.

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
$ php composer.phar require kartik-v/yii2-widgets "dev-master"
```

or add

```
"kartik-v/yii2-widgets": "dev-master"
```

to the ```require``` section of your `composer.json` file.

## Usage

### How to call?
```php
	// add this in your view
	use kartik\widgets\ActiveForm;
	$form = ActiveForm::begin();
```

### ActiveForm
```php
	// Vertical Form
	$form = ActiveForm::begin([
		'id' => 'form-signup',
		'type' => ActiveForm::TYPE_VERTICAL
	]);
  
	// Inline Form
	$form = ActiveForm::begin([
		'id' => 'form-login', 
		'type' => ActiveForm::TYPE_INLINE,
		'fieldConfig' => ['autoPlaceholder'=>true]
	]);

  	// Horizontal Form Configuration
  	$form = ActiveForm::begin([
  		'id' => 'form-signup', 
  		'type' => ActiveForm::TYPE_HORIZONTAL,
		'formConfig' => ['labelSpan' => 3, 'deviceSize' => ActiveForm::SIZE_SMALL]
	]);
```

### ActiveField
```php
	// Prepend an addon text
   	echo $form->field($model, 'email', ['addon' => ['prepend' => ['content'=>'@']]]);
   	
   	// Append an addon text
	echo $form->field($model, 'amount_paid', [
  		'addon' => ['append' => ['content'=>'.00']]
	]);
	
	// Formatted addons (like icons)
	echo $form->field($model, 'phone', [
		'addon' => [
			'prepend' => [
				'content' => '<i class="glyphicon glyphicon-phone"></i>'
			]
		]
	]);
	
	// Formatted addons (inputs)
	echo $form->field($model, 'phone', [
		'addon' => [
			'prepend' => [
				'content' => '<input type="radio">'
			]
		]
	]);
	
	// Formatted addons (buttons)
	echo $form->field($model, 'phone', [
		'addon' => [
			'prepend' => [
				'content' => Html::button('Go', ['class'=>'btn btn-primary'])
			]
			'asButton' => true
		]
	]);
```

### Select2
```php
	// Normal select with ActiveForm & model
	echo $form->field($model, 'state_1')->widget(Select2::classname(), [
		'data' => array_merge(["" => ""], $data),
		'language' => 'de',
		'options' => ['placeholder' => 'Select a state ...'],
		'pluginOptions' => [
			'allowClear' => true
		],
	]);

	// Multiple select without model
	echo Select2::widget([
		'name' => 'state_2',
		'value' => '',
		'data' => $data,
		'options' => ['multiple' => true, 'placeholder' => 'Select states ...']
	]);
```

### Typeahead
```php
use kartik\widgets\Typeahead;

// usage with ActiveForm and model
echo $form->field($model, 'state_3')->widget(Typeahead::classname(), [
	'options' => ['placeholder' => 'Filter as you type ...'],
	'dataset' => [
		[
			'local' => $data,
			'limit' => 10
		]
	]
]);
```

### DatePicker
```php
use kartik\widgets\DatePicker;

// usage without model
echo '<label>Check Issue Date</label>';
echo DatePicker::widget([
	'name' => 'check_issue_date', 
	'value' => date('d-M-Y', strtotime('+2 days')),
	'options' => ['placeholder' => 'Select issue date ...'],
	'pluginOptions' => [
		'format' => 'dd-M-yyyy',
		'todayHighlight' => true
	]
]);
```

### TimePicker
```php
use kartik\widgets\TimePicker;

// usage without model
echo '<label>Start Time</label>';
echo TimePicker::widget([
	'name' => 'start_time', 
	'value' => '11:24 AM',
	'pluginOptions' => [
		'showSeconds' => true
	]
]);
```

### TouchSpin
```php
use kartik\widgets\TouchSpin;

echo TouchSpin::widget([
    'name' => 'volume',
    'options' => ['placeholder' => 'Adjust...'],
    'pluginOptions' => ['step' => 1]
]);
```

### FileInput
```php
use kartik\widgets\FileInput;

// Usage with ActiveForm and model
echo $form->field($model, 'avatar')->widget(FileInput::classname(), [
    'options' => ['accept' => 'image/*'],
]);

// With model & without ActiveForm
echo '<label class="control-label">Add Attachments</label>';
echo FileInput::widget([
    'model' => $model,
    'attribute' => 'attachment_1',
    'options' => ['multiple' => true]
]);
```

### ColorInput
```php
use kartik\widgets\ColorInput;

// Usage with ActiveForm and model
echo $form->field($model, 'color')->widget(ColorInput::classname(), [
    'options' => ['placeholder' => 'Select color ...'],
]);

// With model & without ActiveForm
echo '<label class="control-label">Select Color</label>';
echo ColorInput::widget([
    'model' => $model,
    'attribute' => 'saturation',
]);
```

### RangeInput
```php
use kartik\widgets\RangeInput;

// Usage with ActiveForm and model
echo $form->field($model, 'rating')->widget(RangeInput::classname(), [
    'options' => ['placeholder' => 'Select color ...'],
    'html5Options' => ['min'=>0, 'max'=>1, 'step'=>1],
    'addon' => ['append'=>['content'=>'star']]
]);

// With model & without ActiveForm
echo '<label class="control-label">Adjust Contrast</label>';
echo RangeInput::widget([
    'model' => $model,
    'attribute' => 'contrast',
    'addon' => ['append'=>['content'=>'%']]
]);
```

### Affix
```php
$content = 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.';
$items = [[
	'url' => '#sec-1',
	'label' => 'Section 1',
	'icon' => 'play-circle',
	'content' => $content,
	'items' => [
		['url' => '#sec-1-1', 'label' => 'Section 1.1', 'content' => $content],
		['url' => '#sec-1-2', 'label' => 'Section 1.2', 'content' => $content],
		['url' => '#sec-1-3', 'label' => 'Section 1.3', 'content' => $content],
		['url' => '#sec-1-4', 'label' => 'Section 1.4', 'content' => $content],
		['url' => '#sec-1-5', 'label' => 'Section 1.5', 'content' => $content],
	],
]];

// Displays sidebar menu
echo Affix::widget([
	'items' => $items, 
	'type' => 'menu'
]);

// Displays body sections
echo Affix::widget([
	'items' => $items, 
	'type' => 'body'
]);
```

### SideNav
```php
use kartik\widgets\SideNav;
     
echo SideNav::widget([
	'type' => SideNav::TYPE_DEFAULT,
	'heading' => 'Options',
	'items' => [
		[
			'url' => '#',
			'label' => 'Home',
			'icon' => 'home'
		],
		[
			'label' => 'Help',
			'icon' => 'question-sign',
			'items' => [
				['label' => 'About', 'icon'=>'info-sign', 'url'=>'#'],
				['label' => 'Contact', 'icon'=>'phone', 'url'=>'#'],
			],
		],
	],
]);
```

## License

**yii2-widgets** is released under the BSD 3-Clause License. See the bundled `LICENSE.md` for details.
