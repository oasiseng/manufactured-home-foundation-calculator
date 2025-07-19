2. Open `index.html` in your web browser.

Alternatively, download the ZIP and open the HTML file directly.

## Usage

1. Select or enter values for home width, foundation type, soil type, wind zone, seismic zone, and home length.
2. Optionally check "Include Engineer Inspection Estimate".
3. Click **Calculate** to view results.
4. Review foundation dimensions, tie-down requirements, and cost estimates.
5. Note: Costs are material-only approximations; actual prices vary. For walls in high seismic areas, spacing is reduced for safety.

### Example

- Home Width: 16 ft
- Foundation Type: Footing with Masonry Blocks
- Soil Type: Sandy (medium, 2000 psf)
- Wind Zone: Zone II – 120 mph
- Seismic Zone: Low (No adjustment)
- Home Length: 60 ft
- Include Inspection: Checked

**Result:** 
- Piers: ~22 block stacks (approx. 10 per beam line)
- Footings: 18x18 in x 8 in each
- Spacing: ~7 ft apart
- Anchors: 22 total (11 per side)
- Anchor Spacing: ~6 ft
- Anchor Type: Frame, vertical (over-the-top), and longitudinal straps
- Costs: Foundation ~$440, Tie-Downs ~$660, Inspection $450, Total $1,550

## Technical Details

- **Calculations:** Based on HUD PFGMH (HUD 7584) standards, using a base design load of 100 psf. Footing sizes rounded up with safety factor; pier spacing adjusted for soil and seismic; tie-downs per wind zone.
- **Prescriptive Check:** Aligns with HUD guidelines for pier lines (2-3 based on width), minimum sizes, and anchor types.
- **Limitations:** Assumes basic conditions; does not include snow loads, custom loads, or full engineering analysis. Maximum home length 100 ft.

## Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

1. Fork the project.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This tool provides estimates only and is not a substitute for professional engineering advice. Calculations are based on simplified assumptions from HUD PFGMH (HUD 7584) as of 2025. Verify all designs with a licensed structural engineer to ensure compliance with local codes and site-specific conditions. Oasis Engineering assumes no liability for any use of this tool or for any errors, omissions, or damages arising from its use.

## Acknowledgments

- Inspired by HUD Permanent Foundations Guide for Manufactured Housing.
- Image sourced from PFGMH 4930.3G.

If you find this useful, star the repo! ⭐
