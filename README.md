***************** GUIDE FOR IMPORTANT FUNCTIONS FOR THIS ALI's CORE FRAMEWORK **************

------------------------------------------------------------------------------------------------
App::setErrReporting(false); // Start or stop error reporting
------------------------------------------------------------------------------------------------
$records = $db->query('select * from `table`'); // Make sql query
------------------------------------------------------------------------------------------------
$db->enableQueryLog(false); // Eable or disable query log
------------------------------------------------------------------------------------------------
$db->showDBLog(); // Print query log
------------------------------------------------------------------------------------------------
dump('Message'); or dump(array('Message1','Message2')); // dump any message or array
------------------------------------------------------------------------------------------------
dd('Message'); or dump(array('Message1','Message2')); // dump & die(stop execution) after print message or array 
------------------------------------------------------------------------------------------------
$app->redirect('url'); // Redirect to any url
------------------------------------------------------------------------------------------------
$app->destroySession(); // Destroying current session
------------------------------------------------------------------------------------------------
$app->setSession('key','value'); // Set session value
------------------------------------------------------------------------------------------------
$app->getSession('key'); // Get session value
------------------------------------------------------------------------------------------------
$app->removeSession('key'); // Remove session value
------------------------------------------------------------------------------------------------
$app->logout('OptionalredirectTo'); // Logout function for user management sites , you can optionally pass url to be redirected after logout
------------------------------------------------------------------------------------------------
encrypt('stringtoencrypt'); // encrypt functin that is useful to encrypt any string
------------------------------------------------------------------------------------------------


There are other important functions as well , you can find them in the common folder and appropriate .php file.

================================================================================================
                  THANK YOU FOR USING ALI's COREFRAMEWORK
================================================================================================
