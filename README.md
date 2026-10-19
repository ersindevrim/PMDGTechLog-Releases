# PMDG TechLog

**A tech log, MEL, part wear and failures for the PMDG 737 (-600, -700, -800, -900) in Microsoft Flight Simulator 2024.** Free.

Every time you load the aircraft it is brand new. PMDG TechLog gives each airframe a memory: wear, defects, fuel and a record of every flight carry on from one session to the next. Parts fail from how you fly, the failure is set in the PMDG through its own FAILURES pages, and you fix or defer it against an MEL.

This is a test build. It has been tried by a small group of people, so expect rough edges.

## Download

**[Get the latest version](https://github.com/ersindevrim/PMDGTechLog-releases/releases/latest)**: download `PMDGTechLog-Setup-vX.Y.Z.exe` and run it with the simulator closed.

## What it does

- **Persistent aircraft.** Open and deferred defects are set in the PMDG again every session. Fuel, tyre pressures, brake and tyre wear, oil, hours and cycles carry on. One record per registration.
- **Failures with a cause, not dice.** 134 part types each have their own life. Worn parts show a fault first, then fail when they work hardest.
- **Damage the moment it happens.** Hard landings, flap and gear overspeeds, tail strikes, hot brakes, takeoff thrust held too long.
- **Tech log with an MEL.** 205 items in TechLog's own wording, for simulation use. NO-GO grounds the aircraft; the rest you fix, or defer to a real date.
- **Performance page.** Takeoff and landing figures from the PMDG's own tablet calculator, and Send to FMC.
- **Cockpit page and SimBrief.** Save and restore the 737's switches; import your latest SimBrief plan.

## You need

- Windows 10 or 11 (64-bit)
- Microsoft Flight Simulator 2024
- The PMDG 737
- The Performance page needs Developer Mode in the sim (Options > General Options > Developers > Developer Mode).

## Install

1. Download the setup from the [latest release](https://github.com/ersindevrim/PMDGTechLog-releases/releases/latest) and run it.
2. If Windows SmartScreen appears, choose **More info**, then **Run anyway**. The installer is not code-signed.
3. Start the simulator, load the PMDG 737, and open PMDG TechLog.
4. If your CDU type (the PMDG's OPT EQUIP page) is FANS 2/B, set the same in PMDG TechLog's Settings, PMDG and the sim, CDU type.

## Bug reports

Open an [issue](https://github.com/ersindevrim/PMDGTechLog-releases/issues). Say which 737 variant you fly and what the CDU type is.

## Licence

Freeware, closed source. See `LICENSE.txt` and `THIRD-PARTY-NOTICES.txt`.
