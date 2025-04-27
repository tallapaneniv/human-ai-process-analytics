# README for data used in human-ai-process-analytics

## Overview 
Data used for manuscript: They are proprietary datasets, Trace_data and essayLog data. Both of them have the data that can be used to study the Human-AI interaction.
***

## Purpose of the study 
This project will apply various process mining techniques on an anonymized dataset of human-AI collaboration, to reveal and compare interaction patterns. Deliverables will include code and a concise report with visualizations.


## Structure of the data
Note: Columns should have information about units, number of levels, or format where appropriate.
#### trace_data (sample).xlsx
###### Data set #1
* \#
* user_id
* save_time
* url
* source
* page_event
* target_object
* instant_event
* sub_action_label
* screen x
* screen y
* client x
* client y
* window_inner_width
* window_inner_height
* screen_width
* screen_height
* event_value
* action_label
* process_label
* course_id
* detailed_action_label
* model_type

I have categorised these feature into 3 kinds - irrelevent, neutral, and useful. based on their usability to the project. irrelevent features are the features I deemed are not useful, likewise neutral features include the features that i have yet to find use for but not completely hopeless. Lastly useful features include all the features That I deemed to be relevent and useful for the project.


irrelevent - url, process_label, course_id, detailed_action_label, and model_type


neutral - #, save_time, page_event, target_object, screen x, screen y, client x, client y, window_inner_width, window_inner_height, screen_width, and screen_height


useful - user_id, source, instant_event, sub_action_label, event_value, and action_label

#### essayLog (sample).xlsx
###### Data set #2
* \#
* user_id
* save_time
* url
* essay_content
* essay_content_json
* course_id

For now I have not had the need to use this essay dataset
***
