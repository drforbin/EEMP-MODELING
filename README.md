Enhanced EMP modeling (all of these enhancements made by) Merlyn(Drforbin)Cousins.

The enhancements are the general cleanup of code and the ability to write plot data 
to a gnuplot file for later viewing.

The procedure for compile and first run are as follows;

gfortran -o empplot EMPNPLT_FG2_plot.f

./empplot <IN3x.txt

gnuplot -p gnuplot_draw

DF(MC)
