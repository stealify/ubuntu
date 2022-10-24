# subuntu project - Super Ubuntu
subuntu not Stealify Ubuntu it is simply Super Ubuntu a ubuntu distribution using stealify at ring 0 as also everything on edge merging incremental to ubuntu/debian into @stealify/os it is the Prefered Development Environment till Stealify OS Reaches Standalone State.

## Vision
As Stealify FS offers a uniq layer that allows us to deploy multiple container formats virtual via btrfs we can create a ubuntu distro that can use
all package-managers via container abstractions of virtual composed filesystem trees and then compose out of that none containered nativ filesystems.
This allows us to incremental migrate port ubuntu and the dart stack to the Stealify Component System and the kernel parts to the @stealify/hardware system to create a stealify/os expirence. while we can create a minimal stealify/os already. this is a effort to make it adopt able by ubuntu users.

## Goals
- [ ] install and run the stealify component manager and [runtime](https://github.com/stealify/stealify) as also schedule it via SystemD
- [ ] install and run the stealify VSStudio Component core UI for the OS till gnome is replaced. to have a uniq foundation we can build on while we incremental port and merge everything!
  - [ ] briding the container systems via @stealify/fs 
  - [ ] Integrate DBUS Tasks for gnome and other integrations. 
  - [ ] Replace SystemD with Stealify Component Manager Running @stealify/os component at ring 0 
  - [ ] Integrate AsteriskGL *GL as core Graphics Layer and driver
    - [ ] Integrate Wayland / Mir / x11 compat including Joining The Wayland Root Compositor via Components into a Single x11 Session again!
      - [ ] better x11 wayland interop via exposing the framebuffer sets compose able as components defined out of Tasks. 
  - [ ] Replace pipe wire with our Stealify Component Manager where a Pipe is a Task between components.
  - [ ] Replace gnome with @stealify/webplatform and desktop task and components. 
  - [ ] Integrate tooling for gnome, cinnamon, etc... desklets and widgeds notifications
  - [ ] Implement own permission system on top of the fdo universal exchange concepts event driven file processing defined by location of the link.
  - [ ] StealifyFS integration 
  - [ ] Stealify KVM VMM Integration
  - [ ] Incremental start with porting over all core dependencies. via implementing rmlint style deduplication on source levels. 
  
