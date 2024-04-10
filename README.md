<!DOCTYPE html>
<html>

<body> 
	<h2>General description</h2>
	<br>
	<p>
		The library rest service performs the role of a library, taking into account the authentification of incoming users, management of books, publishers, authors, locations and ratings.
		The data source is CSV files, separate for each entity.
	<p>
	<br>
	<br>
	<h2>Business logic descriptions<h2>
	<br>
	<h3>Authors<h3>
	<p>
		All authors have unique names. Creating a new author with the same name or updating the name of the current author will result in an error.
	<p>
	<br>
	<h3>Publishers<h3>
	<p>
		All publishers have unique names. Creating a new publishers with the same name or updating the name of the current publishers will result in an error.
	<p>
	<br>
	<h3>Books<h3>
	<p>
		Each book has a unique isbn. Creating a book with the same isbn or changing the isbn will result in an error.
	<p>
	<h3>Book ratings<h3>
	<p>
		Each user can leave only one review about a particular book. If a user tries to leave a second review about the same book, it will lead to an error.
	<p>
</body>

</html>