# homework3
<script>
    const a = 700;
    const b = 8000;

    if(a === b) {
        console.log('a is the same as b');
    } else if(a > b) {
        console.log('a is greater than b');
    } else {
        console.log('a is less than b');
    }
    
     // make a function, put it into a variable
    const a = function() {
        console.log('Samvel');
        console.log('Hakobyan');
        console.log('AUA');
    };

    a(); // call the function
    a(); // call the function again
    
    const reverse = function (str) {
        if (str === "") {
            return "";
        } else {
            return reverse(str.substring(1)) + str.substring(0, 1);
        }
    };

    console.log(reverse('SamvelHakobyan'));
    
     console.log(!'hi everybody');
     
     
</script>
