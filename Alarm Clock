import datetime
import winsound,time

def sound():
    for i in range(4): #Number of times it repeats
        for j in range(4): #Number of beeps
            winsound.MessageBeep(-1) #Sound played
        time.sleep(2) #How long between beeps

AlarmHour = int(input('At what hour do you want to wake up? '))
AlarmMinute = int(input('At what minute do you want to wake up? '))
AmPm = str(input('am or pm? '))

print('Waiting for {} : {} {}'.format(AlarmHour,AlarmMinute,AmPm))

if (AmPm == 'pm'):
    AlarmHour = AlarmHour + 12
    
while True:
    if (AlarmHour == datetime.datetime.now().hour and AlarmMinute == datetime.datetime.now().minute):
        print('Wake up!')
        sound()
        break
        
print('Exit!')
