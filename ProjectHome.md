MAE (Multi-purpose Annotation Environment) is an annotation tool created by Amber Stubbs (http://amberstubbs.net) for Brandeis University for use in her dissertation research. It is a lightweight program written in Java, with a MySQLite database back end (SQLiteJDBC driver created by David Crawshaw (http://www.zentus.com/sqlitejdbc/)).

MAE allows users to define their own annotation tasks, annotate partial words, use non-consuming tags, easily create links between annotations, and it outputs annotations in stand-off XML. While it does not enforce strict rules for annotation schemes, it is very easy to set up and start running.

The current version of MAE is **0.9.6**.  A .zip file containing the .jar file, a user guide, readme.txt and example files is available on the download page.  The SVN repository contains the Eclipse workspace for the project, as well as fairly complete Javadocs (more information will be added as MAE progresses).

MAE version 0.9.6 fixes a problem with deleting table entries encountered when sorting the tables based on different columns, and re-introduces the functionality which scrolls the text to the appropriate location when a tag ID is double-clicked.

The Multi-document Adjudication Interface (MAI) is a companion program to MAE that allows you to create gold standard files from multiple annotations of the same document.  MAI is available for download at http://code.google.com/p/mai-adjudication/.

If you wish to cite MAE in a publication, please use:
Amber Stubbs. "MAE and MAI: Lightweight Annotation and Adjudication Tools". In 2011 Proceedings of the Linguistic Annotation Workshop V, Association of Computational Linguistics, Portland, Oregon, July 23-24, 2011.