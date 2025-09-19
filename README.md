# Trading Sessions with High/Low Levels

[![TradingView](https://img.shields.io/badge/TradingView-Indicator-blue?logo=tradingview&logoColor=white)](https://es.tradingview.com/script/NaTeSqvh/)

A comprehensive Pine Script indicator for TradingView that provides visual background coloring for major trading sessions along with dynamic high/low level tracking and labeling.

Access the indicator directly on TradingView: [Trading Sessions with High/Low Levels](https://es.tradingview.com/script/NaTeSqvh/)

![Trading Sessions with HighLow Levels Preview](https://i.imgur.com/UEYCk4Y.png)

## Overview

This advanced indicator combines session background highlighting with precise high/low level detection for each trading session. It tracks and displays the highest and lowest price levels reached during Asia, London, and USA trading sessions, with customizable visual elements including lines, labels, and background colors.

## Background / Evolution

This indicator is an evolution of the previous **"Trading Sessions Background Color"** indicator, now featuring high/low level tracking, labels, and more customization options.  

You can find the original indicator here:  
- [Trading Sessions Background Color on TradingView](https://es.tradingview.com/script/Pmi5dzPc/)  
- [Trading Sessions Background Color on GitHub](https://github.com/Devilquest/Trading-Sessions-Background-Color)

## Features

- **Three Major Trading Sessions**: Asia, London, and USA sessions with default time ranges.
- **High/Low Level Tracking**: Automatic detection and display of session highs and lows.
- **Dynamic Line Drawing**: Horizontal lines marking key levels with customizable styling.
- **Price Labels**: Optional labels showing exact high/low values.
- **Session Background Colors**: Customizable background highlighting for active sessions.
- **Historical Session Display**: View multiple previous sessions simultaneously.
- **Current Day Filter**: Option to display only today's sessions.
- **Line Extension Control**: Choose between session-bound or current bar extension.
- **Timezone Adjustment**: Built-in UTC offset adjustment for local timezone compatibility.
- **Comprehensive Customization**: Individual control over colors, styles, and visibility for each session.

## Default Session Times

| Session | Default Time Range (UTC) | Default Background Color | Default Line Color |
|---------|-------------------------|-------------------------|-------------------|
| Asia    | 02:00 - 09:00          | Red (90% transparency)   | Red |
| London  | 09:00 - 15:00          | Green (90% transparency) | Green |
| USA     | 15:00 - 23:00          | Blue (90% transparency)  | Blue |

**Note**: All sessions are fully configurable - you can modify names, time ranges, colors, and visual properties according to your specific trading requirements.

## Configuration Options

### Session-Specific Settings
Each trading session includes the following configurable parameters:

**Background Options:**
- **Show session background**: Toggle to enable/disable background coloring.
- **Session background color**: Background color with transparency control.

**Session Definition:**
- **Name**: Custom label for the session.
- **Session time**: Time range in HHMM-HHMM format.

**Line Options:**
- **Show High/Low lines**: Toggle to enable/disable level lines.
- **Line/Label color**: Color for both lines and labels.
- **Line width**: Thickness of the lines (1-5 pixels).
- **Line style**: Choose between Solid, Dashed, or Dotted lines.

**Label Options:**
- **Show High/Low labels**: Toggle to enable/disable price labels.
- **Label text color**: Text color for price labels.
- **Label size**: Choose between Tiny, Small, Normal, or Large.

### High/Low Lines Options
- **Number of sessions to show lines**: Display 1-21 previous sessions (ignored when current day filter is active).
- **Only show current day sessions**: Filter to display only today's sessions.
- **Extend lines to current bar**: Choose between session-bound lines or extension to current price action.

### Global Options
- **UTC Time Zone Adjustment**: Offset value (-12 to +14) to match your local timezone.

## Usage Instructions

1. Add the indicator to your TradingView chart.
2. Configure desired trading sessions in the settings:
   - Enable/disable background colors and high/low lines independently.
   - Customize colors, line styles, and label properties.
   - Set appropriate time ranges for your market focus.
3. Adjust high/low line options:
   - Set number of historical sessions to display.
   - Enable current day filter if needed.
   - Choose line extension preference.
4. Set the UTC offset to match your local timezone.
5. Apply the settings.

## Timezone Configuration

The indicator uses a custom UTC offset system. To configure for your timezone:

**Examples:**
- **New York (EST)**: Set UTC offset to `-5` (or `-4` during DST).
- **London (GMT)**: Set UTC offset to `0` (or `+1` during BST).
- **Tokyo (JST)**: Set UTC offset to `+9`.
- **Sydney (AEST)**: Set UTC offset to `+10` (or `+11` during AEDT).

## Key Functionality

### Session Tracking
- **Real-time Detection**: Automatically identifies session start/end times.
- **High/Low Calculation**: Tracks extreme values throughout each session.
- **Historical Storage**: Maintains chronological record of completed sessions.

### Visual Elements
- **Background Coloring**: Independent control for each session's background.
- **Horizontal Lines**: Precise level marking with customizable styling.
- **Price Labels**: Centered labels showing exact high/low values.
- **Line Management**: Automatic cleanup of old visual elements.

### Display Modes
- **Historical View**: Show multiple previous sessions for pattern analysis.
- **Current Day Focus**: Filter to display only today's activity.
- **Line Extension**: Choose between session-specific or current bar alignment.

## Limitations

- **Intraday Only**: The indicator will display an error on daily, weekly, or monthly timeframes.
- **Session Overlap**: Multiple sessions may overlap, with colors and lines layering based on execution order.
- **Maximum of three sessions**: Currently supports three configurable sessions. 
- **Line Limit**: Maximum of 500 lines enforced by TradingView platform.

---

**Note**: This indicator is designed for educational and analytical purposes. Always conduct your own research and risk management when trading.

<br>

------------
## :heart:Donations
**Donations are always greatly appreciated. Thank you for your support!**

<a href="https://www.buymeacoffee.com/devilquest" target="_blank"><img src="https://i.imgur.com/RHHFQWs.png" alt="Buy Me A Dinosaur"></a>