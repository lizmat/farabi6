Farabi6
=======

This is a fun Perl 6 port of the Farabi Modern Perl Editor http://metacpan.org/module/Farabi.
The idea here is to experiment with a Perl 6 in-browser editor running over Rakudo Perl 6. 

Please Note that this project is highly **experimental** and may explode in your face. You have been warned :)

Have fun!

## Installation

To run it from the local directory:

    bin/farabi6
    # Open http://localhost:3030 in your browser

To install it using Panda:

    panda install Farabi6
    farabi6
    # Open http://localhost:3030 in your browser

You can also change the host name and port using the following command:

    farabi6 --host=localhost --port=4040

## Testing

To run tests:

    prove -e perl6

## Author

Ahmad M. Zawawi, azawawi on #perl6, https://github.com/azawawi/

## License

Artistic License 2.0
