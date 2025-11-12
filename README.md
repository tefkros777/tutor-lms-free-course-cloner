# Course Cloner for Tutor LMS (Free)

A fully custom plugin to duplicate courses in Tutor LMS free on WordPress.

Course cloning is a normally a Pro feature. This plugin will create a Course Cloner entry in the WP-Admin panel. Just select your course from the dropdown list and click clone. The new course ID will be shown and the newly created course will have a "draft" status. 

After the cloning remember to visit wp-admin/edit.php?post_type=courses and change its name, add a post category (just copy the original course's category) and change its slug. Then publish.

This was successfully testes to clone the Course and its metadata including topics, lessons and content, quizzes and their answers but it has not been tested with assignments yet. It does not copy enrolled students or any student data as this would usually be unwanted.
