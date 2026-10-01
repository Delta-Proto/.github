<p align="center">
  <a href="https://deltaproto.com"><img src="https://deltaproto.com/static/images/logos/deltaproto.svg" width="110" alt="DeltaProto"></a>
</p>

<h1 align="center">DeltaProto</h1>

<p align="center">
  <strong>Your design, built faster.</strong><br>
  Price in seconds. Offer in minutes. First PCBA in days.
</p>

## What we do

DeltaProto is a proto PCBA lab in the Netherlands, with locations in Amsterdam and Enschede. We take a hardware design from files to assembled prototypes in days: we source the PCB and the components, assemble by machine and by hand, and ship a **First Proto** so you can test and change the design before the rest of the order is built. More than 90% of our customers change something between the first sample and the next, and that is the point.

Hardware teams across the Netherlands, Belgium and Germany use us to iterate faster.

- **[Calculator](https://deltaproto.com/calculator)** – upload your Gerber, BOM and centroid and see a price in seconds
- **[Wiki](https://deltaproto.com/info/wiki)** – what we need from you: the [Bill of Materials](https://deltaproto.com/info/wiki/bom), the [Gerber and drill set](https://deltaproto.com/info/wiki/gerber), the [centroid](https://deltaproto.com/info/wiki/centroid), and the [parts and suppliers](https://deltaproto.com/info/wiki/parts) we buy from
- **[Insights](https://deltaproto.com/insights)** – notes from the lab on lead times, iterations and design for prototyping

## Open source

We write our own tooling for reading PCB design data, and we publish the parts that are useful to everyone. Both libraries power the viewers on our site.

| Project | What it does | Try it |
|---|---|---|
| **[delta-gerber](https://github.com/Delta-Proto/delta-gerber)** | Java library that parses Gerber RS-274X and Excellon drill files and renders photorealistic PCB views to SVG and PNG, with proper layer stacking. Works with KiCad, Altium, EAGLE and Allegro output. Maven: `com.deltaproto:delta-gerber`. | [Online Gerber viewer](https://deltaproto.com/opensource-gerber-viewer) |
| **[delta-odbpp](https://github.com/Delta-Proto/delta-odbpp)** | Java library that parses ODB++ design archives, renders them to SVG and PNG, and converts them to Gerber X2 + Excellon. Maven: `com.deltaproto:delta-odbpp`. | [Online ODB++ viewer](https://deltaproto.com/opensource-odbpp-viewer) |

Both viewers run in your browser, no install needed.

Found a Gerber or ODB++ file we do not read correctly? Open an issue on the repository with the file attached; that is the fastest way to get it fixed. Pull requests are welcome.

## Example files

These three files describe the same board, the ST Nucleo-L031K6, and show what a complete data set for a proto PCBA looks like:

- [Standardised BOM (xlsx)](https://deltaproto.com/static/DeltaProto%20SBOM%20EN.xlsx)
- [Example Gerber and drill set (zip)](https://deltaproto.com/static/DeltaProto%20gerber%20example.zip)
- [Example centroid (csv)](https://deltaproto.com/static/DeltaProto%20centroid%20example.csv)

## Contact

[deltaproto.com](https://deltaproto.com) · [info@deltaproto.com](mailto:info@deltaproto.com) · +31 20 717 3868 · [LinkedIn](https://www.linkedin.com/company/deltaproto/) · [YouTube](https://www.youtube.com/channel/UCicF5MFJohgYe6IGFs5GJ_w)

DeltaProto B.V. · Hellingweg 8, 1151 CS Broek in Waterland (Amsterdam) · Hengelosestraat 701, 7521 PA Enschede (Twente)
