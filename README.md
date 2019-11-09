# joomla-typehint-classes
This file helps some IDE's like NetBeans, Eclipse to use type hints in joomla projects.
Because joomla has classmap.php where classes are registered and in project used aliases of classes, IDE's can't suggest class paths and go to declarationt etc..
After putting this file in any include path folder then IDE can use joomla typehints.

For example:

class JControllerForm extends Joomla\CMS\MVC\Controller\FormController
{
    
}


