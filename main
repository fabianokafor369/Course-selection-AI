KB = """
%KB


chosen_course(b110) :- major_type(bs), preferred_day(R), memberchk(R, [ monday, tuesday, wednesday, thursday]), preferred_seoul_time(morning), future_major_type(bs), (future_bs_course(P), memberchk(P, [b144, b154, b164, b145, b155, b165, b146, b156, b166])).
chosen_course(b111) :- major_type(bs), preferred_day(R), memberchk(R, [ monday, tuesday, wednesday, thursday]), preferred_seoul_time(S), memberchk(S, [evening, noon]),  future_major_type(bs), (future_bs_course(P), memberchk(P, [b144, b154, b164, b145, b155, b165, b146, b156, b166])).

chosen_course(cS110) :- major_type(cs), preferred_day(R), memberchk(R, [monday, tuesday, wednesday, thursday]), preferred_seoul_time(morning),  future_major_type(cs), future_cs_course(D), memberchk(D, [cs142, cs152, cs162, cs156]).
chosen_course(cS111A) :- major_type(cs), preferred_day(R), memberchk(R, [monday, tuesday, wednesday, thursday]), preferred_seoul_time(morning),  future_major_type(T), memberchk(T, [cs, ns]), (future_cs_course(cs144); future_cs_course(cs154); future_cs_course(cs164); future_cs_course(cs152); future_ns_course(ns142); future_ns_course(ns156)).
chosen_course(cS112) :- major_type(cs), preferred_day(R), memberchk(R, [monday, wednesday]), preferred_seoul_time(night), future_major_type(T), memberchk(T, [cs, ns]), (future_ns_course(ns152); future_ns_course(ns156); future_ns_course(ns162); future_cs_course(cs146); future_cs_course(cs166)).
chosen_course(cS112) :- major_type(cs), preferred_day(R), memberchk(R, [monday, tuesday, wednesday, thursday]), preferred_seoul_time(morning), future_major_type(T), memberchk(T, [cs, ns]), (future_ns_course(ns152); future_ns_course(ns156); future_ns_course(ns162); future_cs_course(cs146); future_cs_course(cs166)).

chosen_course(aH110) :- major_type(ah), memberchk(R, [monday, tuesday, wednesday, thursday]), preferred_seoul_time(morning), future_major_type(ah) , future_ah_course(D), memberchk(D,[ah142,ah152,ah162]) .
chosen_course(aH111) :- major_type(ah),memberchk(R, [monday, tuesday, wednesday]), preferred_seoul_time(morning),  future_major_type(ah) , future_ah_course(D), memberchk(D,[ah144,ah154,ah164]).
chosen_course(aH112) :- major_type(ah), preferred_day(R), memberchk(R, [tuesday, thursday]), preferred_seoul_time(morning),  future_major_type(ah) , future_ah_course(D), memberchk(D,[ah146,ah156,ah166]).
chosen_course(aH112) :- major_type(ah), preferred_day(R), memberchk(R, [monday, wednesday]), preferred_seoul_time(evening), future_major_type(ah) , future_ah_course(D), memberchk(D,[ah146,ah156,ah166]).

chosen_course(sS110) :- major_type(ss), preferred_day(R), memberchk(R, [ monday, tuesday, wednesday, thursday]), preferred_seoul_time(S), memberchk(S, [evening, morning]),   future_major_type(ss) , future_ss_course(D), memberchk(D,[ss142, ss152, ss162]).
chosen_course(sS111) :- major_type(ss),preferred_day(R), memberchk(R, [ monday, tuesday, wednesday, thursday]), preferred_seoul_time(S), memberchk(S, [evening, noon]),  future_major_type(ss) , future_ss_course(D), memberchk(D,[ss144, ss154, ss164]).
chosen_course(sS112) :- major_type(ss), preferred_day(R), memberchk(R, [ monday, tuesday, wednesday, thursday]), preferred_seoul_time(morning), future_major_type(ss) , future_ss_course(D), memberchk(D,[ss146, ss156, ss166]).
chosen_course(sS112) :- major_type(ss), preferred_day(R), memberchk(R, [ tuesday, thursday]), preferred_seoul_time(evening),  future_major_type(ss) , future_ss_course(D), memberchk(D,[ss146, ss156, ss166]).

chosen_course(nS110U) :- major_type(ns), preferred_day(R) memberchk(R, [monday, wednesday]), preferred_seoul_time(morning),  future_major_type(ns) , future_ns_course(D), memberchk(D,[ss142, ss152, ss162]).
chosen_course(nS111) :- major_type(ns),preferred_day(R), memberchk(R, [monday, wednesday]), preferred_seoul_time(morning), future_major_type(ns) , future_ns_course(D), memberchk(D,[ns146, ns156, ns166]).
chosen_course(nS110L) :- major_type(ns), preferred_day(R) memberchk(R, [monday, wednesday]), preferred_seoul_time(morning),  future_major_type(ns) , future_ns_course(D), memberchk(D,[ss152, ss162]).
chosen_course(nS112) :- major_type(ns), preferred_day(R), memberchk(R, [tuesday, thursday]), preferred_seoul_time(morning),  future_major_type(ns) , future_ns_course(D), memberchk(D,[ss144, ss154, ss164]).

chosen_courses(cS112) :-  course_of_interest(ns152); course_of_interest(ns156); course_of_interest(ns162); course_of_interest(cs146); course_of_interest(cs166).
chosen_courses(cS110) :- course_of_interest(D), memberchk(D, [cs142, cs152, cs162, cs156]).
chosen_courses(cS111A) :- course_of_interest(cs144); course_of_interest(cs154); course_of_interest(cs164); course_of_interest(cs152); course_of_interest(ns142); course_of_interest(ns156).
chosen_courses(cS112) :-  course_of_interest(ns152); course_of_interest(ns156); course_of_interest(ns162); course_of_interest(cs146); course_of_interest(cs166).

chosen_courses(aH110) :- course_of_interest(D), memberchk(D,[ah142,ah152,ah162]) .
chosen_courses(aH111) :- course_of_interest(D), memberchk(D,[ah144,ah154,ah164]).
chosen_courses(aH112) :-  course_of_interest(D), memberchk(D,[ah146,ah156,ah166]).

chosen_courses(b111) :- course_of_interest(P), memberchk(P, [b144, b154, b164, b145, b155, b165, b146, b156, b166]).
chosen_courses(b110) :-  course_of_interest(P), memberchk(P, [b144, b154, b164, b145, b155, b165, b146, b156, b166]).

chosen_courses(sS110) :- course_of_interest(D), memberchk(D,[ss142, ss152, ss162]).
chosen_courses(sS111) :-  course_of_interest(D), memberchk(D,[ss144, ss154, ss164]).
chosen_courses(sS112) :- course_of_interest(D), memberchk(D,[ss146, ss156, ss166]).

chosen_courses(nS110U) :-  course_of_interest(D), memberchk(D,[ns142, ns152, ns162]).
chosen_courses(nS111) :- course_of_interest(D), memberchk(D,[ns146, ns156, ns166]).
chosen_courses(nS110L) :-  course_of_interest(D), memberchk(D,[ns152, ns162]).
chosen_courses(nS112) :-  course_of_interest(D), memberchk(D,[ns144, ns154, ns164]).

course_of_interest(X) :- menuask(course_of_interest, X, [b144,b145,b146,b154,b155,b156,b164,b165,b166,cs144, cs142, cs146, cs152,cs154,cs156,cs162,cs164,cs166, ns142,ns144,ns146,ns152,ns154,ns156,ns162,ns164,ns166, ss142,ss146,ss144,ss152,ss154,ss156,ss162,ss164,ss166,ah142,ah144,ah146, ah152, ah154, ah156, ah162, ah164, ah166]).


major_type(X) :-menuask(what_major_would_you_want_to_take_this_class_for, X, [ah, cs, ns, bs, ss]).
preferred_day(X) :- menuask(the_day_you_would_prefer_to_take_this_class_would_be_, X, [monday, tuesday, wednesday, thursday]).
preferred_seoul_time(X) :- menuask(the_time_of_the_day_in_seoul_time_you_prefer_for_this_class_is, X, [morning, noon, evening, night]).
future_major_type(X) :- menuask(what_could_be_a_possible_course_you_want_this_class_to_be_relevant_for_in_future, X, [ah, cs, ns, bs, ss]).
future_bs_course(X) :- future_major_type(bs) , menuask(the_future_bs_course_most_relevant_is, X, [b144,b145,b146,b154,b155,b156,b164,b165,b166]).
future_cs_course(X) :- future_major_type(cs) , menuask(the_future_cs_course_most_relevant_is, X, [cs144, cs142, cs146, cs152,cs154,cs156,cs162,cs164,cs166]).
future_ns_course(X) :- future_major_type(ns) , menuask(the_future_ns_course_most_relevant_is, X, [ns142,ns144,ns146,ns152,ns154,ns156,ns162,ns164,ns166]).
future_ss_course(X) :- future_major_type(ss) , menuask(the_future_ss_course_most_relevant_is, X, [ss142,ss146,ss144,ss152,ss154,ss156,ss162,ss164,ss166]).
future_ah_course(X) :- future_major_type(ah) , menuask(the_future_ah_course_most_relevant_is, X, [ah142,ah144,ah146, ah152, ah154, ah156, ah162, ah164, ah166]).

% The code below implements the prompting to ask the user:
menuask(Attribute,Value,_) :-
  known(yes,Attribute,Value),       % succeed if we know
  !.
  
menuask(Attribute,_,_) :-
  known(yes,Attribute,_),           % fail if its some other value
  !, fail.

menuask(Attribute,AskValue,Menu):-
  menuread(Attribute, Y, Menu),
  asserta(known(yes,Attribute,Y)),
  AskValue = AnswerValue.           % succeed or fail based on answer
"""
with open("KB_B.pl", "w") as text_file:
    text_file.write(KB)
    

    
# The code here will ask the user for input based on the askables
# It will check if the answer is known first
from pyswip.prolog import Prolog
from pyswip.easy import *

prolog = Prolog() # Global handle to interpreter

retractall = Functor("retractall")
known = Functor("known",3)

# Define foreign functions for getting user input and writing to the screen
def menuread(A, Y, Menu):
    Y.unify(raw_input(" ".join(str(A).split('_')).capitalize() +  str([str(i) for i in Menu]) + "?"))
    return True

menuread.arity = 3
registerForeign(menuread)

prolog.consult("KB_B.pl") # open the KB
call(retractall(known))
count = 0
accountant = ['CS112']

print "Hi, My name is Fabian. Welcome to the course selection helper for class of 2021s."
name = raw_input("What would you would you like to be called for the sake of this session?")
print "Welcome " + name + ". If you need help recalling the various courses codes, please visit https://www.minerva.kgi.edu/academics/course_catalog/natural_sciences/"
while True:
    picker = raw_input("What would you like your course selection to be based on? Type in an option [major and time, future course interests]")
    if picker == "major and time":
        for soln in prolog.query("chosen_course(X)."):
            result = soln['X'].split('_')
            result= ' '.join(result).upper()
            accountant.append(result)
            count +=1
        if raw_input("Would you like to proceed with finding more recommendations? Type in an option [yes, no]") == "no":
            break
    elif picker == "future course interests":
        for soln in prolog.query("chosen_courses(X)."):
            result = soln['X'].split('_')
            result= ' '.join(result).upper()
            accountant.append(result)
            count +=1
        if raw_input("Would you like to proceed with finding more recommendations? Type in an option [yes, no]") == "no":
            break
    else:
        print "You haven't made a valid selection. Please try again"

def remove(d):
    f= []
    for num in d:
        if num not in f:
            f.append(num)
    return f

if len(accountant) == 0:
    print "There are no recommendations based on your input"
else:
    print "Thank you "+ name + " for using our service. Your possible classes for the fall of your second year based on your inputs are" + str(remove(accountant)) + ". Don't worry, because CS112 is in high demand, we did you a favor of adding it too."
