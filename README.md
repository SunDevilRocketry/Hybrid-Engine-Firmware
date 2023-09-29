<h1>Hybrid Engine Controller Firmware</h1>

<p>PCB: TBD</p>
<p>MCU: STM32F103C8T6 (Blue Pill)</p>
<p>MPU Architecture: ARM Cortex-M3</p>

<h2>Working Directory Structure</h2>

<p>
app: application code for the flight computer containing source directories

auto: auto-generated code from STM32CubeMX (not compiled into application)

init: Microcontroller initialization and configuration code

lib: third-party libraries for device drivers and middleware, microcontroller pin and peripheral configurations 

mod: Hardware modules containing hardware specific code for SDR boards

</p>