#############################################################
#                                                           #
#  Voodoo Ray                                               #
#  by A Guy Called Gerald                                   #
#                                                           #
#  hand-transcribed by Ade Ward for fun                     #
#  (and to demonstrate the basic caudio syntax, of course)  #
#                                                           #
#  cat ReadMe.txt | ../caudio > /dev/null                   #
#                                                           #
#  WAY COOL! Instant breakdowns using grep!                 #
#  grep -v hi ReadMe.txt | ../caudio > /dev/null            #
#                                                           #
#############################################################

load VoodooHit.wav   as hit
load VoodooBass.wav  as bass
load VoodooHihat.wav as hi
load VoodooSnare.wav as snare
load VoodooRim.wav   as rim
load VoodooTom.wav   as tom
load VoodooDeep.wav  as deep
load VoodooVocal.wav as voc

sleep 200

play voc pitch 55
play deep pitch 60
play bass pan 0
play bass pan 1
play bass
play hit pitch 60
play hi
sleep 110

play tom
play hi pan 0.25
sleep 110

play hi pan 0.75
sleep 110

play rim
play hi
sleep 110

play snare
play hi pan 1
play hit pitch 60
sleep 110

play hi pan 0
sleep 110

play voc pitch 64
play tom pitch 68
play hi
sleep 110

play tom pitch 68
play hi pan 0.25
sleep 110

play hit pitch 69
sleep 110

play hi pan 0.75
sleep 110

play voc pitch 60
play tom pitch 68
play hi
sleep 110

play snare
play hit pitch 69
sleep 110

play rim
play hi pan 0.75
sleep 110

play tom pitch 68
play hi pan 0.25
sleep 110

play hi
play hit pitch 65
sleep 110

play hi pan 0
sleep 110

play deep pitch 57
play bass
play hi pan 1
sleep 110

play tom
play hi
sleep 110

play hi pan 0.75
play hit pitch 65
sleep 110

play rim
play hi pan 0.25
sleep 110

play snare
play hi
sleep 110

play hi pan 0.25
sleep 110

play tom pitch 68
play hi pan 0.75
play hit pitch 65
sleep 110

play tom pitch 68
sleep 110

play voc pitch 65
play hi
play hit pitch 63
sleep 110

play hi pan 1
sleep 110

play tom pitch 68
play hit pitch 65
sleep 110

play snare
play hi pan 0
sleep 110

play rim
play hi pan 0.25
play hit pitch 63
sleep 110

play tom pitch 68
play hi pan 0.75
sleep 110

play hi
sleep 110

play hi pan 1
sleep 110

play voc pitch 63
play deep pitch 60
play bass
play hi pan 0
play hit pitch 60
play hit pitch 55
sleep 110

play tom
play hi
sleep 110

play hi pan 0.25
sleep 110

play rim
play hi pan 0.75
sleep 110

play snare
play hi pan 0.3
play hit pitch 60
play hit pitch 55
sleep 110

play hi pan 0.7
sleep 110

play voc pitch 60
play tom pitch 68
play hi pan 0.4
sleep 110

play tom pitch 68
play hi pan 0.6
sleep 110

play hit pitch 69
sleep 110

play hi
sleep 110

play tom pitch 68
play hi pan 0.45
sleep 110

play snare
play hit pitch 69
sleep 110

play rim
play hi pan 0.55
sleep 110

play tom pitch 68
play hi
sleep 110

play hi
play hit pitch 65
sleep 110

play hi pan 0.25
sleep 110

play deep pitch 53
play bass
play hi pan 0.75
sleep 110

play tom
play hi
sleep 110

play hi pan 0.75
play hit pitch 65
sleep 110

play rim
play hi pan 0.25
sleep 110

play snare
play hi
sleep 110

play hi pan 0
sleep 110

play tom pitch 68
play hi pan 1
play hit pitch 65
sleep 110

play tom pitch 68
play hi
sleep 110

play hit pitch 63
sleep 110

play hi pan 1
sleep 110

play tom pitch 68
play hi pan 0
sleep 110

play snare
sleep 110

play rim
play hi
play hit pitch 63
sleep 110

play tom pitch 68
play hi pan 0
sleep 110

play hi pan 1
sleep 110

play hi
sleep 110

quit

