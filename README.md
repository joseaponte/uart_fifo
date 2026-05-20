# UART Core With FIFO and Register Interface

> A UART transmitter/receiver with configurabe baud rate, TX/RX FIFOs,
status flags, and a simple memory-mapped register interface.

## Modules

```text
uart_top
├── baud_generator
├── uart_tx
├── uart_rx
├── fifo_sync
└── register_file
```

## Verification

> Use cocotb to send bytes, receive bytes, test framming errors, FIFO full/empty, and different baud rates

## Objectives
> Design and verify an UART peripheral that demonstrate:
>
> - Finite State Machine design
> - Counter-based timing generation
> - FIFO-based data buffering
> - Clocked Synchronous logic
> - Status and control register implementation
> - RTL simulation and verification
> - Basic hardware/software interaction