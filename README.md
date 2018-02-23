# WebClicker

## Abstractions

The library have to abstract following areas. This way it should be easier to migrate it to a potential new technology.
* Web Engine
* Interactive / Background execution
* Consistent clicker syntax

## Web Engine

The idea is to reuse WebBrowser controls (WinForm / WFP / both). Later it can be extended to support Chrome or Edge (for the time being it's not possible to embed Edge in applications). Even maybe to use raw WebClient class.

## Interactive / Background execution

There sould be 2 exectuion modes.
* Interactive - with GUI to present web content
* Background - without GUI, to be executed as servicce, CI chaing, etc.

## Clicker syntex

Should be intuitive and consistent. Should support blocking and async calls.
