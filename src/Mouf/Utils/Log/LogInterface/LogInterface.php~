<?php
/*
 * Copyright (c) 2012 David Negrier
 * 
 * See the file LICENSE.txt for copying permission.
 */


/**
 * This is the base interface any logger should inherit.
 * It provides logging capabilities at 6 different levels:
 * - trace
 * - debug
 * - info
 * - warn
 * - error
 * - fatal
 *
 */
interface LogInterface {
	
	/**
	 * Logs a message in the error log as a TRACE message.
	 * This function takes 1 or 2 arguments:
	 *
	 * @param string $string The string to log
	 * @param Exception $e The exception to log
	 * @param array $additional_parameters An array of additional parameters (that can depend on the logger used)
	 */
	function trace($string, Exception $e=null, array $additional_parameters=array());
	
	/**
	 * Logs a message in the error log as a DEBUG message.
	 * This function takes 1 or 2 arguments:
	 *
	 * @param string $string The string to log
	 * @param Exception $e The exception to log
	 * @param array $additional_parameters An array of additional parameters (that can depend on the logger used)
	 */
	function debug($string, Exception $e=null, array $additional_parameters=array());
	
	/**
	 * Logs a message in the error log as a INFO message.
	 * This function takes 1 or 2 arguments:
	 *
	 * @param string $string The string to log
	 * @param Exception $e The exception to log
	 * @param array $additional_parameters An array of additional parameters (that can depend on the logger used)
	 */
	function info($string, Exception $e=null, array $additional_parameters=array());
	
	/**
	 * Logs a message in the error log as a WARN message.
	 * This function takes 1 or 2 arguments:
	 *
	 * @param string $string The string to log
	 * @param Exception $e The exception to log
	 * @param array $additional_parameters An array of additional parameters (that can depend on the logger used)
	 */
	function warn($string, Exception $e=null, array $additional_parameters=array());
	
	/**
	 * Logs a message in the error log as a ERROR message.
	 * This function takes 1 or 2 arguments:
	 *
	 * @param string $string The string to log
	 * @param Exception $e The exception to log
	 * @param array $additional_parameters An array of additional parameters (that can depend on the logger used)
	 */
	function error($string, Exception $e=null, array $additional_parameters=array());
	
	/**
	 * Logs a message in the error log as a FATAL message.
	 * This function takes 1 or 2 arguments:
	 *
	 * @param string $string The string to log
	 * @param Exception $e The exception to log
	 * @param array $additional_parameters An array of additional parameters (that can depend on the logger used)
	 */
	function fatal($string, Exception $e=null, array $additional_parameters=array());
	
}
?>