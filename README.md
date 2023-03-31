# contact

<script>
$( document ).ready(function() {
$( ".button-contacts" ).click(function(e){
    e.preventDefault();
    console.log('testing');
    var email = $('input#ContactForm-email').val();

    console.log('email',email);

    if(email== '') {
$(this).parents('.custom_contact').find('.form__message.custom-error').show();
$(this).parents('.custom_contact').find('.form-status-list.caption-large.custom-error').show();
    }else{
    $('form#ContactForm').trigger('submit');
        console.log('aaaaaaa');
        
    }
    
   });
  });
</script>
