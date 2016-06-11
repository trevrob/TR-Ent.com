$('.myForm').on('submit', function(event){
    event.preventDefault(); 
    $.ajax({
        url: $(this).attr('action'),
        type: $(this).attr('method'),
        data: $(this).serialize(),
        success: function(html) {
        alert('ok');
        }
    });
    $('.done').css('display','block');
    $(".myForm")[0].reset();
    //return false; 
});
