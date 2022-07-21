# book-ever

AIzaSyDE989LnmEjVNKzDojFm9AWJOFWtmjfH2A

fetch(`https://www.googleapis.com/books/v1/volumes?q=search-terms&key=AIzaSyDE989LnmEjVNKzDojFm9AWJOFWtmjfH2A`)
.then(response => console.log(response))
.then(result => {({ books: result.items})
})
