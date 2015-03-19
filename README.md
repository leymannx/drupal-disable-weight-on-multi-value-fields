# [Drupal] Disable weight option for multi value fields

This module isn't writte by me. Brad Czerniak did it and shared the code:
http://www.commercialprogression.com/post/how-remove-tabledrag-rearranging-multiple-value-field-widgets

All you have to do is change the field name for which you want to disable weight within hook_field_widget_form_alter()

- name = Multi Widget Remove Tabledrag
- description = Brad Czerniak wrote this module to disable weighting for selected multi value fields
- core = 7.x
- package = Custom
