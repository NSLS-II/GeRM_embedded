# GeRM
Code for the embedded IOC in the GeRM and Hera detectors.
NSLS-II has developed a series of X-ray detectors based on in-house developed ASICs and sensors. They are all multi-detector systems based on monolithic multi-element sensors and independent readout of each element via multiple 32-channel ASICs. The devices are controlled by a Xilinx Zynq Series 7 SOC. The ASIC configuration is performed by the FPGA logic, and high-level controls by an embedded EPICS IOC running Linux on its dual-core Arm processors. The series contains a number of variants. Germanium detectors having 64, 96, 192and 384 elements exist. Detectors based on multielement Silicon Drift Detectors are under development. They are called Hera. A 96-element version exists, and a 384-element version si under development. Although the FPGA code varies for all of them, the embedded IOC interface is the same.