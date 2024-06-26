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
