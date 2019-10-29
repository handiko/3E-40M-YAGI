# 3 Elements Fullsize Yagi Antenna for 40m Band
Here is presented 2 models of 3 elements fullsize yagi antenna for 40m band.
The first model is optimized for the compact boomlength of 16 meters while keep maintain good VSWR < 1:1.5, gain, and F/B ratio. The second model is optimized for lowest SWR while keep maintain the boom length below 18 meters otherwise. All models are simulated for the installation height of about 24 meters using 4nec-2 software package.

![](./panoramic.png)

## Dimensions
The picture below will tell thousands words. Please left click / right click + open in new tab for the full view of the picture.
![](./yagi-diagram.png)

**Tuning procedure:**
* Mount the antenna at the real installation height, or at least 7 m above the ground.
* Tune the 15 m band driven element for the lowest VSWR at 21.05 MHz. Adjust both end simultaneously.
* Tune the 10 m band driven element for the lowest VSWR at 28.05 MHz. Adjust both end simultaneously.
* Back to 15 m band and check if whether the VSWR shift after 10 m band tuning. If so, then re-adjust the 15 m band driven element.
* Again, back to 10 m band and check again. Repeat this procedure until VSWR is satifying at both band.

**Typical VSWR:**
* 15m band; 1.04:1 at 21.05 MHz
* 10m band; 1.12:1 at 28.05 MHz

**Typical gain:**
* 15m band (10 m above ground); 11.5 dBi
* 10m band (10 m above ground); 12.4 dBi

## Simulation Results (15m Band)
![](./VSWR15.png)
![](./patt15.png)

## Simulation Results (10m Band)
![](./VSWR10.png)
![](./patt10.png)

## Propagation Map Simulation (VOACAP Online, May 2019)
**15m band at 9 UTC**
![](./prop15peak.png)

**10m band at 11 UTC**
![](./prop10peak.png)

## Contributing
1. Fork it [https://github.com/handiko/3E-40M-YAGI/fork](https://github.com/handiko/3E-40M-YAGI/fork)
2. Create new branch (`git checkout -b myfeature`)
3. Do some editing / create new feature
4. Commit your works (`git commit -m "Adding some myfeature blah blah.."`)
5. Push to the branch (`git push -u origin myfeature`)
6. Create a new Pull Request
