#----------------------------------------------------------------------
# Makefile.am  -  FINAL CUT example programs
#----------------------------------------------------------------------

if ! CPPUNIT_TEST

AM_LDFLAGS = -L$(top_builddir)/src/.libs -lfinal
AM_CPPFLAGS = -I$(top_srcdir)/src/include -Wall -Werror -std=c++11

noinst_PROGRAMS = \
	hello \
	dialog \
	input-dialog \
	event-log \
	fullwidth-character \
	7segment \
	choice \
	busy \
	listbox \
	listview \
	checklist \
	treeview \
	opti-move \
	termcap \
	string-operations \
	mandelbrot \
	rotozoomer \
	calculator \
	watch \
	term-attributes \
	background-color \
	transparent \
	keyboard \
	mouse \
	timer \
	scrollview \
	windows \
	menu \
	ui

hello_SOURCES = hello.cpp
dialog_SOURCES = dialog.cpp
input_dialog_SOURCES = input-dialog.cpp
event_log_SOURCES = event-log.cpp
fullwidth_character_SOURCES = fullwidth-character.cpp
7segment_SOURCES = 7segment.cpp
choice_SOURCES = choice.cpp
busy_SOURCES = busy.cpp
listbox_SOURCES = listbox.cpp
listview_SOURCES = listview.cpp
checklist_SOURCES = checklist.cpp
treeview_SOURCES = treeview.cpp
opti_move_SOURCES = opti-move.cpp
string_operations_SOURCES = string-operations.cpp
mandelbrot_SOURCES = mandelbrot.cpp
rotozoomer_SOURCES = rotozoomer.cpp
calculator_SOURCES = calculator.cpp
watch_SOURCES = watch.cpp
term_attributes_SOURCES = term-attributes.cpp
background_color_SOURCES = background-color.cpp
termcap_SOURCES = termcap.cpp
transparent_SOURCES = transparent.cpp
keyboard_SOURCES = keyboard.cpp
mouse_SOURCES = mouse.cpp
timer_SOURCES = timer.cpp
scrollview_SOURCES = scrollview.cpp
windows_SOURCES = windows.cpp
menu_SOURCES = menu.cpp
ui_SOURCES = ui.cpp

endif

clean-local:
	-find . \( -name "*.gcda" -o -name "*.gcno" -o -name "*.gcov" \) -delete
