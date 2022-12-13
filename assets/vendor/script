$(document).ready(function() {
	// animation library
	AOS.init({
  	duration: 1200,
   	once: true
	})
  
  var scrollTop = $('.back-to-top img');

  $(window).scroll(function() {
    var topPos = $(this).scrollTop();

    // if user scrolls down - show scroll to top button
    if (topPos > 100) {
      $(scrollTop).css("opacity", "1");
    } else {
      $(scrollTop).css("opacity", "0");
    }
  });
  
  // click event to scroll to top
  $(scrollTop).click(function() {
    $('html, body').animate({
      scrollTop: 0
    }, 800);
    return false;
	});
});
