Class **Phalcon\\Mvc\\Model\\ValidationFailed**
===============================================

*extends* class :doc:`Phalcon\\Mvc\\Model\\Exception <Phalcon_Mvc_Model_Exception>`

*implements* Throwable

.. role:: raw-html(raw)
   :format: html

:raw-html:`<a href="https://github.com/dreamsxin/cphalcon7/blob/master/ext/mvc/model/validationfailed.c" class="btn btn-default btn-sm">Source on GitHub</a>`

This exception is generated when a model fails to save a record Phalcon\\Mvc\\Model must be set up to have this behavior


Methods
-------

public  **__construct** (:doc:`Phalcon\\Mvc\\Model <Phalcon_Mvc_Model>` $model, *Phalcon\\Mvc\\Model\\Message[]* $validationMessages)

Phalcon\\Mvc\\Model\\ValidationFailed constructor



public *Phalcon\\Mvc\\Model\\Message[]*  **getMessages** ()

Returns the complete group of messages produced in the validation



public :doc:`Phalcon\\Mvc\\Model <Phalcon_Mvc_Model>`  **getModel** ()

Returns the model that generated the messages



final private *Exception*  **__clone** () inherited from Exception

Clone the exception



public  **__wakeup** () inherited from Exception

...


final public *string*  **getMessage** () inherited from Exception

Gets the Exception message



final public *int*  **getCode** () inherited from Exception

Gets the Exception code



final public *string*  **getFile** () inherited from Exception

Gets the file in which the exception occurred



final public *int*  **getLine** () inherited from Exception

Gets the line in which the exception occurred



final public *array*  **getTrace** () inherited from Exception

Gets the stack trace



final public *Exception*  **getPrevious** () inherited from Exception

Returns previous Exception



final public *Exception*  **getTraceAsString** () inherited from Exception

Gets the stack trace as a string



public *string*  **__toString** () inherited from Exception

String representation of the exception



