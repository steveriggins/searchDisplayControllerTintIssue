Overview
=======

This application is an example of an issue run into on iOS 5.

This project has two UISearchBar objects in a view controller.  Both UISearchBars have the same tint color.  One of them (the right one) is connected to a UISearchDisplayController.

If you run this project on a 4.3 iPhone or Simulator, both UISearchBars look the same.

If you run this project on a 5.0 iPhone or Simulator, the right search bar looks much more washed out.

UISearchBars with no tint look the same on both OSes regardless of being connected to a UISearchDisplayController or not.

Is this a bug in iOS 5?