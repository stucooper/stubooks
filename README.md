# stubooks

This project, surely of interest only to myself, tracks books
that I own.

Publisher abbreviations:
ORA	O'Reilly and Associates https://www.oreilly.com
PTR     Prentice Hall
AWL     Addison Wesley (Longman)
MK      Morgan Kaufmann and Elsevier

Book abbreviations:
2e,3e   2nd edition, 3rd edition
cftbl   Coffee Table sized book; hardback (usually) and huge (always)

Location abbreviations:
lcb    Little Creatures Box (empty beer case)
lc2    Little Creatures Box Newer Design Newer Box
cib    Cisco Box
pcp    Penguin Classics Plastic - large plastic box of Penguin Classics
whb    Wodehouse box: Vacuum Cleaner box garage middle left
brc    Back Right Corner: far corner right at the back. Buried under brm
brm    Back Right Middle. This box is on top of Back Right Corner (brc)
cor    Coopers Red Box (empty beer case)
mtb    Monteiths Beer Box (empty beer case)
hbc    Hillbilly Cider box (empty cider case)
pcg    Perl Cooper's Green (two of these)
mt2    Monteiths Black Beer second box
pib    Pink plastic box, in my own bedroom
bed    My Bedroom. These books should be in sight of my bedroom
bsgp   Bookshelf Green Pile. My Bookshelf Green ORA Web/Javascript books

lending abbreviations:
cmc/CMC Charles Cave, Epping

Handy scripts and greps
============================

./count: Produce a (more or less accurate) count of my physical books;
         grepping out "lost?" books, comment lines etc. This script
	 creates a (non-git saved) file called allbooks

egrep -v '(19|20)' ora_classic.txt: List files without 1998 2012
                                    publication dates

grep R20 wodehouse.txt: List books reviewed in my "booksiveread" project.
