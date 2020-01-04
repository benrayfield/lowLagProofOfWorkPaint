# lowLagProofOfWorkPaint
millions of people watching thousands (or everyone equally if possible) of people paint together in realtime at gaming-low-lag, organized by take max of proof-of-work divided by chosen volume in a 3d (x y time) by double-sha256, so at each x y time its instantly sync-able globally whats the colorRGB - See what ppl realtime dream together 

For example, data of the form 6 doubles then 3 bytes: xStart xEnd yStart yEnd timeStart timeEnd redByte greenByte blueByte, aka 51 bytes (1 cycle sha256 is at most 55 bytes), double-sha256-ed to sort by which r g b 24bits are the color at each 3d point (x y time). Nonce can be chosen as the low bits of those 6 doubles, since the smaller a volume you choose the less time you have to spread it across the world vs a bigger volume needs less precision so you have more space for proofOfWork.

Planning prototype in java using weupnp peer-to-peer networking, with some few servers to boot the network, maybe.

I expect this software to either be ignored or change the world while being about 30 kB of code (other than Java). Its a simple concept but could motivate game-theory between potentially millions or billions of people at once.
