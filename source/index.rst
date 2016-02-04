.. diffusionkit documentation master file, created by
   sphinx-quickstart on Mon Oct 26 10:48:55 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

..
	 Welcome to DiffusionKit's documentation!
	 ========================================

	 Table of Contents
	 =================

Homepage
========

Welcome to Brainnetome DiffusionKit's Homepage
-----------------------------------------------

..
	 What is Brainnetome DiffusionKit?
	 **********************************

Brainnetome DiffusionKit is a light one-stop cross-platform solution to dMRI data analysis. 
The package delivers a complete pipeline from data format conversion to preprocessing, 
from local reconstruction to fiber tracking, and from fiber statistics to visualization.

..
	 What does Brainnetome DiffusionKit consist of?
	 ***********************************************

It was developed as a cross-platform framework, 
using ITK `[1] <reference.html#id1>`_ for computation, 
VTK `[2] <reference.html#id2>`_ for visualization, and Qt for GUI design. 
Both GPU and CPU computing were implemented for visualization to achieve high frame-rate, 
for rendering complex scene like whole brain tractographs in particular. 
The project was managed using the compiler-independent CMake `[3] <reference.html#id3>`_, 
which is compatible with gcc/g++ and MS Visual Studio, etc. 
Well-established algorithms, such as the DICOM conversion tool dcm2nii by 
Chris Rorden `[4] <reference.html#id4>`_ and the constrained spherical deconvolution (CSD) for 
HARDI reconstruction in MRtrix `[5] <reference.html#id5>`_, 
were adopted with improved interface and user experience.

For new users, and/or for an overview of DiffusionKit’s basic functionality, 
please see the `Tutorial <tutorial.html>`_. 
The rest of the documentation will assume you’re at least passingly familiar with the 
material contained within.

*Please see the navigation sidebar to the left to begin.*

..
	 This site covers DiffusionKit’s usage & API documentation. 
	 For basic info on what DiffusionKit is, including its public changelog & how the project is maintained, 
	 please see the main project website.

	 Tutorial
	 --------

	 Usage documentation
	 -------------------

	 The following list contains all major sections of DiffusionKit’s prose (non-API) documentation, 
	 which expands upon the concepts outlined in the Overview and Tutorial and also covers advanced topics.

.. toctree::
   :maxdepth: 1
   
   document.rst
   screenshot.rst
   download.rst
   license.rst
   faq.rst
   feedback.rst

.. note:: Document last updated on |today|.

.. 
 Reference
 *********
 .. [1] http://www.itk.org
 .. [2] http://www.vtk.org
 .. [3] http://www.cmake.org
 .. [4] http://www.mccauslandcenter.sc.edu/mricro
 .. [5] http://www.nitrc.org/projects/mrtrix

.. include:: common.txt

.. raw:: html

 <script type="text/javascript">
 $(window).load(function(){
 $('.toctree-wrapper').hide();
 $('.reference').css('font-size','10pt');
 $('.fn-backref').css('font-size','10pt');
 $('h1').hide();
 $('td').css('padding','2px');
 });
 </script>