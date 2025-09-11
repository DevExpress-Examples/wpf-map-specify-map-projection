<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571850/21.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T232417)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# How to specify a map projection

This example demonstrates how to specify a map projection that is used to display geographical data for a Map Control. 
## Files to Look at
<!-- default file list -->
* [MainWindow.xaml](./CS/MapProjections/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MapProjections/MainWindow.xaml))
<!-- default file list end -->

## Example Overview

To configure a map projection, specify the [GeoMapCoordinateSystem.Projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.GeoMapCoordinateSystem.Projection) property of the [GeoMapCoordinateSystem](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.GeoMapCoordinateSystem) object, which should be assigned to the [MapControl.CoordinateSystem](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.MapControl.CoordinateSystem).

One of the following predefined map projections can be used:
- [Braun stereographic projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.BraunStereographicProjection)
- [Elliptical Mercator projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.EllipticalMercatorProjection)
- [Equal-area projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.EqualAreaProjection)
- [Equidistant projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.EquidistantProjection)
- [Equirectangular projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.EquirectangularProjection)
- [Kavrayskiy projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.KavrayskiyProjection)
- [Lambert Cylindrical Equal-area projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.LambertCylindricalEqualAreaProjection)
- [Miller projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.MillerProjection)
- [Sinusoidal projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.SinusoidalProjection)
- [Spherical Mercator projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.SphericalMercatorProjection)
- [ Lambert Azimuthal Equal-Area Projection](https://docs.devexpress.com/WPF/DevExpress.Xpf.Map.Etrs89LambertAzimuthalEqualAreaProjection)

## Documentation 

- [How to: Specify a Map Projection](https://docs.devexpress.com/WPF/113972/controls-and-libraries/map-control/examples/vector-data/customize-data-appearance/how-to-specify-a-map-projection)
- [Geographical Projections](https://docs.devexpress.com/WPF/14750/controls-and-libraries/map-control/coordinate-systems/geographical-projections)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-map-specify-map-projection&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-map-specify-map-projection&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
