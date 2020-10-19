# iOSCharts.Xamarin

A Xamarin binding by Lucas Teixeira for Charts (ios-charts) by Daniel Cohen Gindi, inspired by Philipp Jahoda
https://github.com/danielgindi/Charts

<h2>Charts 3.6.0</h2>
<p>Requires Xcode 12+. To see the release notes go to: https://github.com/danielgindi/Charts/releases</p>

<p>Projects using this library must also include the latest version of [Xamarin.iOS.SwiftRuntimeSupport](https://www.nuget.org/packages/Xamarin.iOS.SwiftRuntimeSupport/).</p>

<h2>Publishing to the App Store</h2>
<p>Since we're deploying to iOS 12, you must run a script to copy the Swift support files to the proper location in the IPA. If you don't complete this step, Apple will reject the upload with an error regarding missing Swift Support libraries.</p>

<p>Our Bitrise project will automatically run this script as part of app store builds. If you're performing a local app store build, be sure to follow the [Tiered Local Builds](https://ifitdev.atlassian.net/wiki/spaces/RWA/pages/811040783/Tiered+Local+Builds) guide.</p>

<h2>Binding Swift Libraries</h2>
<p>If you got here after googling for a way to bind Swift libraries in Xamarin, you may find this Documentation useful: stackoverflow.com/documentation/xamarin.ios/6091/binding-swift-libraries</p>

<p>In case you wish help, feel free to contact me https://twitter.com/flash3001</p>

<h2>License</h2>
<p>Copyright 2017 Lucas Teixeira, Daniel Cohen Gindi & Philipp Jahoda</p>

<p>Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.</p>
