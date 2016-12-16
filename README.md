# Close-Bootstrap-Drop-Down-Menu-OnClick

A simple jQuery snippet to close the Bootstrap Dropdown Menu on click

$("document").ready(function () {
	$('.navbar-collapse ul li a:not(.dropdown-toggle)').click(function () { 
         $('.navbar-toggle:visible').click(); 
    }); 
});
