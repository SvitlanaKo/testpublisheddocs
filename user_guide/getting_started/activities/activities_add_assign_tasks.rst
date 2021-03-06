.. _user-guide-activities-tasks:

Tasks
=====

In order to save information on certain actions to be performed or issues to be resolved by a user, you can
create a task in one of the ways described below.

Create a Task
-------------
There are several ways to create a task:

- Use the **Add Task** action to create a task in the context of some entity record and define the user responsible.

- Use the **Assign Task** action on the page of the user responsible.

- Create a **Task** records in the Tasks grid.


Add a Task for Another Record
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. important::
    By default, the list of activities available for each entity is determined by what is most commonly used by businesses. However, if your company's work process requires it, you can always turn the desirable activity on for almost any entity (except technical ones). If you need particular activities to be enabled for an entity, contact your administrator, or see steps 4 and 5 of the :ref:`Create an Entity <doc-entity-actions-create>` action description

1. Open the View page of a record the task is related to.

2. Click :guilabel:`Add Task` in the :ref:`actions <user-guide-ui-components-view-page-actions>` tab.

3. The **Add Task** page appears. The form has the following fields:

.. csv-table::
  :header: "**Name**","**Description**"
  :widths: 10, 30

  "**Subject***","The task title. Must be defined."
  "**Description**","A free text tab. Contains the task description. The field may be left empty."
  "**Due date**","Defines the date the task is due from the calendar (if any)."
  "**Priority***","Defines if the task priority. The possible values are: 
  
  - *Low*
  - *Normal*
  - *High*
  
  The field is by default set to *Normal*."
  "**Assigned To***","Choose the user, to whom the task is assigned. By default, the field is by default filled in with 
  name of the user, creating the task."
  "**Reminders**","Defines if a message must be sent to the user defined in the *Assigned to* field with regard to the 
  task.
  
  Click the :guilabel:`Add` button to add a reminder.

   - Define if the message will be an email or a flash message, as well as how long before the time defined in the 
     *Due date* it will be sent. 

  Reminders cannot be defined if the due date hasn't been defined."
   
For example, we want Ellen Rowell from the sales to replace the email address of Jeffrey Maynard, who has recently 
changed his work. 

We have created a relevant task on the View page of Jeffrey Maynard's contact record.  The task must be done within
a week (till April 5th). An email will be sent to Ellen Rowell one day before the due date.

      |
  
.. image:: /user_guide/img/getting_started/activities/add_task_ex.png
   
4. Click the :guilabel:`Create Task` button and the Task will be added.


.. _user-guide-activities-tasks-assign:

Assign a Task to a User
^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to the View page of the user record, for which the task is assigned.

2. Click :guilabel:`Assign Task` in the :ref:`actions <user-guide-ui-components-view-page-actions>` tab.

3. The **Assign Task to {user name}** page appears.

   The form has the same fields as the "Add Task" form. The "Assigned to" field value is the user you have chosen, and 
   it cannot be edited.

For example, we also need Ellen Rowell to find a new contact at Cal Stereo, where Mr. Jeffrey Maynard used to work.
The task has no specific due date, but its priority is high.

      |
  
.. image:: /user_guide/img/getting_started/activities/assign_task.png

4. Click the :guilabel:`Create Task` button and the task will be added.


Create a Task from the Tasks Grid
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Navigate to **Activities > Tasks** or click the :guilable`Tasks` button above your calendar.

2. Click the :guilabel:`Create Task` button.

3. The **Create Task** page appears.

      |

.. image:: /user_guide/img/getting_started/activities/create_task.png

The form has the same fields as the **Add Task** page. By default, the **Assigned to** field is filled with the user
creating the task but it can be edited.

This is a particularly convenient way to create a task for yourself, as well as for other users.


View and Manage Tasks
^^^^^^^^^^^^^^^^^^^^^

.. note::

   The ability to view and edit the tasks depends on specific roles and permissions defined for them in 
   the system. 
   
- All the tasks can be viewed for the Tasks grid.

- All the events added for a record are displayed and can be reached from the **Record Activities** section on the
  View page of this record:

  |
  
.. image:: /user_guide/img/getting_started/activities/add_task_view.png


- To see the details, click on the task title or the :guilabel:`+` to the left from it.  

- All the tasks assigned to a user will appear in the **User Tasks** grid in the **Additional Information** section of the
  user's View page. 

.. image:: /user_guide/img/getting_started/activities/assign_task_manage.png


From any of the grids above, you can manage the tasks using the action icons:

- Delete the task: |IcDelete|

- Get to the :ref:`Edit form <user-guide-ui-components-create-pages>` of the task: |IcEdit|

- Get to the :ref:`View page <user-guide-ui-components-view-pages>` of the task:  |IcView|

      |

Tasks Assigned to You
"""""""""""""""""""""

Once you have logged into the system, you can see the Task grid in the **My Tasks** page.

.. image:: /user_guide/img/getting_started/activities/my_tasks_menu.png

.. image:: /user_guide/img/getting_started/activities/my_tasks.png


Tasks, for which a due date has been defined will also appear in the **My Calendar** page:

      |
  
.. image:: /user_guide/img/getting_started/activities/my_tasks_cal.png


Click on the task in the calendar to get to its information tab. Use the buttons at the bottom to manage the task.

      |
  
.. image:: /user_guide/img/getting_started/activities/my_tasks_info.png



.. .. note::

..    The tasks can also be mapped to the Outlook account as described in the corresponding
    :ref:`section <outlook-calendar-mapping>` of the
    :ref:`Synchronization with Outlook guide <user-guide-synch-outlook>`.

.. include:: /user_guide/include_images.rst
   :start-after: begin
