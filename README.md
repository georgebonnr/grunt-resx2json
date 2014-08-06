grunt-resx2json
==============

Grunt task for converting .resx files into json

**Installation**  
`npm install grunt-resx2json`  
  
**Usage**  
`grunt resx2json`  

*Fork has been hacked / simplified from original:*

	grunt.initConfig({
		foo: {
			files : [
	    		{src: 'foo.resx', dest: 'foo.json'}
	    	],
	    },

	  	bar: {
	    	files : [
	    		{src: 'bar.resx', dest: 'bar.json'}
	    		{src: 'barTwo.resx', dest: 'barTwo.json'}
	    	]
	  	}