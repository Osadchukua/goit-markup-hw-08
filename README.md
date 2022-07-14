від 480 до 1200 
@media screen and (min-width 480px) and (max-width 1200px){ 
    .div{ 
    color: tomato;
    }
}

до 480 і від 1200 
@media screen and (max-width 480px) and (min-width 1200px){ 
    .div{ 
    color: tomato;
    }
}

до 480
@mixin mobile {
   @media screen and (min-width: 480px) {
        @content;
    }
}



1:24:00 1x 2x - https://www.youtube.com/watch?v=l0vpazfkcpQ&ab_channel=GoIT