sassificator
============

css to sass converter

no convertion from sass back to css

and no tests. sorry.

Class params are specified in class's comments

Usage:

	sassificator_instance = Sassificator.new
	sass_hash_obj = sassificator_instance.get_sass_str_and_sass_obj css_input_text_code

Output
	
	:sass_obj 		- sass hierarchy object
	:sass_string	- sass_formated string