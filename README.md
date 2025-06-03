# utl-some-sas-I982-base-sas-manual-pages-with-proc-matrix-pages
Some sas 1982 base sas manual pages with proc matrix pages
    %let pgm=utl-some-sas-I982-base-sas-manual-pages-with-proc-matrix-pages;

    %stop_submission;

    Some sas 1982 base sas manual pages with proc matrix pages

    manual pages
    https://tinyurl.com/yntb5hyd
    https://github.com/rogerjdeangelis/utl-some-sas-I982-base-sas-manual-pages-with-proc-matrix-pages/blob/main/sas1982.pdf

    github
    https://tinyurl.com/yu2erb7p
    https://github.com/rogerjdeangelis/utl-some-sas-I982-base-sas-manual-pages-with-proc-matrix-pages

    SAS 1982 PROC MATRIX EXAMPLE

    PROC MATRIX;
       /* Define a matrix A */
       A = (1 2, 3 4);
       /* Define a vector b */
       b = (5, 6);
       /* Solve the system Ax = b */
       x = INV(A) * b;
       PRINT x;
    RUN;
