<h1>DMA Controller Intel 8237A (simplified)</h1>
I realized this Verilog implementation with my two colleagues Vittorio Sali and Francesco Interlandi as a project for the course in Architettura dei Calcolatori (Computer Architecture) we took in university in 2023.

<h2>What can I find in this repository?</h2>
The implementation of the device is not complete in relation to the original device sold by Intel, as not all the functions described in the original datasheet are not present.
In particular, Memory-to-Memory Transfer mode and Dummy Transfer mode have not been implemented. Moreover due to the complexity required for the synchronizations of transfers, a TestBench for Cascade mode was not realized, even though an immplementation is present in the Verilog code.

<ul>
  <li>Verilog code: the actual implementation of the device that me and my colleagues wrote.</li>
  <li>Images: pictures of some example outputs of the Verilog code used in different working modes. GTKWave has been used to run the code and generate those images.</li>
</ul>
