# WRChance
WR Chance will be a module for LiveSplit.  The build is a modified version of SethBling's PBChance, which can be found at https://github.com/SethBling/PBChance

## What it is:

WRChance is a LiveSplit component that tracks your previous performances for your splits.  When you give it a target time, it tells you the odds that you will achieve this time, based off of your previous attempts.  It will display two different odds:

Performance Odds: purely based off of your previous attempts.
Real Odds: based off of your previous attempts as well as the likelihood that you will reset the run in the current and future splits.

## Everything below this is a work in progress

## Installation:

1. Place PBChance.dll into the Components directory of your LiveSplit installation.
2. Open LiveSplit. Right click -> Edit Layout -> [Giant "+" Button] -> Information -> PB Chance
3. You can configure how many of your most recent attempts will be used to calculate the PB chance. Go to Layout Settings and click on the PB Chance tab. You can either have it use a percentage of your most recent attempts, or just a fixed number of your most recent attempts.
4. Speedrun!

## Pictures:

[The component in action.](http://i.imgur.com/YIjln5P.png)

[The configuration screen.](http://i.imgur.com/CgUuB46.png)

## Troubleshooting:

**It always displays "0%" or "-"**

You may need to configure the plugin to use a different number of attempts. For instance, it may not be reading any attempts in which you've completed a run. Additionally, you may have reset your split data at some point, which will remove the data necessary for PBChance to calculate its probability. If you want to debug the issue, try opening your splits file in a text editor (it's XML formatted). You may be able to spot missing splits, and it will inform you how to configure the PBChance component.
