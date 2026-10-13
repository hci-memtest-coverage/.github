# HCI MemTest - Cover Free RAM with a Pattern Test

[![Open HCI MemTest](https://img.shields.io/badge/Open-HCI_MemTest-7c2d12?style=for-the-badge&logo=windows&logoColor=white)](https://lauritanoguez55.github.io/.github/hci-memtest-coverage)

## At a Glance

HCI MemTest asks how much memory to test and then walks patterns across that allocation. Windows will not give it every byte. You run enough instances, or one large one, so the covered total is most of the installed RAM, and you leave them until coverage is high. An error in any instance is a fail. Stop and fix the profile or the seating before you run a longer test on a broken setting.

- Coverage you actually add up
- Other heavy programs closed
- Errors treated as final for this BIOS profile
- A note of the speed you tested
- No repair button

1. Reboot to the RAM settings you want to judge.
2. Start the test and set the allocation.
3. Open more instances if one cannot cover the installed size.
4. Wait until coverage is meaningful, not just started.
5. Stop at the first error if you are still tuning.

## Fits

A Windows RAM check after new memory or a new profile. A poor fit for a disk failure. A poor fit for a one-minute run you call a pass. A poor fit if the page file is thrashing because you allocated more than the system can hold. Test RAM, do not force the disk to pretend it is RAM.

## Requirements

| Item | Expectation |
|---|---|
| RAM | The settings you intend to keep |
| OS | A quiet Windows session |
| Time | Hours if you want a serious coverage number |
| Power | Plugged in on a laptop |

![HCI MemTest coverage percentage on a quiet Windows session](https://i.ytimg.com/vi/chxIIehbo8Y/maxresdefault.jpg)

## Fixes

It tests far less than you installed. Start another instance or close the program that is holding RAM.
Errors appear at the rated profile. That profile is not stable here. Loosen it within the vendor's limits or replace the kit.
The PC reboots. Count that as a fail.
A long pass and one game still crashes. Look at the GPU and the game.
You ran it once at stock and then enabled XMP. The stock pass does not cover the new profile.

## Coverage Is the Result

HCI MemTest did not test RAM it could not allocate. Add the coverage numbers from every instance and compare them with the installed size. A pretty window on two gigabytes of a 32 GB kit is a smoke test. Close browsers and game launchers, then start enough instances to cover most of the memory. One error fails the profile you are running. Do not average it with a later pass. Drop the memory speed or the tight timings in the BIOS, reboot, and test the new setting from the start.

Stock settings and an XMP profile are different tests. A pass you ran before enabling the profile says nothing about the profile. Write the speed, the timings, and the voltage next to the result. A reboot with no error line is still a fail. A long pass that still leaves one game crashing means you look at the GPU and the game next, not at a third day of the same memory test.

| Outcome | Decision |
|---|---|
| Error in the first minute | Stop, loosen this profile |
| Error after an hour | Still a fail |
| Coverage far below installed RAM | The test was incomplete |
| Full coverage, no errors | Reasonable for this setting |
| Pass at stock, then you enable XMP | Test again |

Plug a laptop in. Battery power limits change clocks and make the run a different test from the one you will use on AC.

## Add Up the Coverage

Each HCI MemTest window only tests the RAM it allocated. One small instance on a large kit is not a pass. Close other programs, start enough copies to cover most of the installed memory, and add the coverage together. An error in any window fails this BIOS profile. Stop, loosen the speed or the timings inside the vendor's limits, and start again. Do not average an error with a later clean run.

A pass at stock settings does not cover the XMP or EXPO profile you enable afterward. Write speed, timings, and voltage next to the result. A reboot with no error text is still a fail. A long pass that leaves one game crashing means the GPU or the game is next. Plug a laptop in. Battery limits make a different test.

- Quiet Windows session
- Coverage compared with installed size
- First error ends the search
- Profile written down
- Stock and XMP tested separately
- Page file not used as pretend RAM
- Hours reserved if you want a serious number

| Result | Call |
|---|---|
| Immediate errors | This profile is unusable |
| Late error | Still a fail |
| Low coverage | Incomplete |
| Full pass | Reasonable for this setting |

The tool does not change the BIOS for you.

## Naming Notes

hci memtest, hci memtest coverage, ram test windows, hci design memtest, memory error coverage, hci memtest multiple instances, ram profile test, hci memtest windows
