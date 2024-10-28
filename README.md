# Need-inspiration-
<?xml version="1.0" encoding="UTF-8"?>
<ScreenTimeTracker>
    <AppInfo>
        <Title>Screen Time Tracker</Title>
        <Description>A simple application to track screen time and display motivational quotes.</Description>
    </AppInfo>
    <Buttons>
        <Button id="startBtn" action="start">Start</Button>
        <Button id="stopBtn" action="stop" disabled="true">Stop</Button>
    </Buttons>
    <Display>
        <TimeDisplay id="timeDisplay">Screen Time: 0 seconds</TimeDisplay>
    </Display>
    <Tracking>
        <Interval time="1000" unit="milliseconds" />
        <Quotes>
            <Quote>Keep going! You're doing great!</Quote>
            <Quote>Believe in yourself!</Quote>
            <Quote>You are capable of amazing things!</Quote>
            <Quote>Stay positive, work hard, make it happen!</Quote>
            <Quote>Success is not for the lazy.</Quote>
        </Quotes>
    </Tracking>
</ScreenTimeTracker>
