# Artificial Intelligence in Unreal Engine 5

<a href="https://www.packtpub.com/en-us/product/artificial-intelligence-in-unreal-engine-5-9781836205852"><img src="https://content.packt.com/B31016/cover_image_small.jpg" alt="" height="256px" align="right"></a>

This is the code repository for [Artificial Intelligence in Unreal Engine 5](https://www.packtpub.com/en-us/product/artificial-intelligence-in-unreal-engine-5-9781836205852), published by Packt.

**Unleash the power of AI for next-gen game development with UE5 by using Blueprints and C++**

## What is this book about?
Have you ever wondered how to create engaging gameplay experiences that involve formidable AI opponents, capable of challenging and pushing players to their limits? If the answer is yes, then get ready to enter the realm of AI creation with Unreal Engine 5.
	
This book covers the following exciting features:
* Discover the basics of AI development in video games
* Gain a deep understanding of the main actors in the Unreal Engine AI framework
* Design and develop engaging AI actors for a game
* Create dynamic and immersive AI experiences with behavior trees, navigation systems, MassEntity, and other AI features
* Debug AI systems using dedicated Unreal Engine debugging tools
* Extend the AI system with custom nodes and functions
* Understand how to cope with the AI system by employing Blueprints and/or C++
* Create games that focus on tactics, motion, and more

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1836205856) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations

The code will look like the following:
```
#pragma once

UENUM(BlueprintType)
enum class EBatteryStatus : uint8
{
    EBS_Empty = 0 UMETA(DisplayName = "Empty"),
    EBS_Low = 1 UMETA(DisplayName = "Low"),
    EBS_Medium = 2 UMETA(DisplayName = "Medium"),
    EBS_Full = 3 UMETA(DisplayName = "Full")
};
```

**Following is what you need for this book:**

This book is for game programmers, as well as Unreal Engine developers with little to no knowledge of AI systems in video games, who want to explore this topic in depth. Developers who are proficient in other game engines and are interested in understanding the principles of the Unreal AI framework will also benefit from this book. You’ll need basic knowledge of Unreal Engine and C++ and a strong passion for game development to get the most out of this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-14).

## Software and Hardware List

| Chapter  | Software required                                       | OS required                      |
| -------- | --------------------------------------------------------| ---------------------------------|
| 1-14     | Unreal Engine 5.4                                       | Windows, macOS, or Linux         |
| 1-14     | Visual Studio 2019 or 2022 and JetBrains Rider 2023+    | Windows, macOS, or Linux         |

## Additional Information

_**Important Note**: the following project files have been created by using Unreal Engine 5.4. However, with a minor effort, you will be able to run the project with Unreal Engine 5.5 or higher._

### Part 2

#### Chapter 4 - Setting Up a Navigation Mesh

* [Unreal Agility Arena - Starter Content](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/starter-content/unrealagilityarena-starter-content.zip) (13.50 MB)
* [Unreal Agility Arena - Chapter 04 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter04-end/unrealagilityarena-chapter-04-end.zip) (13.52 MB)

#### Chapter 5 - Improving Agent Navigation

* [Unreal Agility Arena - Chapter 05 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter05-end/unrealagilityarena-chapter-05-end.zip) (13.65 MB)

### Part 3

#### Chapter 8 - Setting up a Behavior Tree

* [Unreal Agility Arena - Chapter 08 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter08-end/unrealagilityarena-chapter-08-end.zip) (13.6 MB)

#### Chapter 9 - Extending Behavior Trees

* [Unreal Agility Arena - Chapter 09 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter09-end/unrealagilityarena-chapter-09-end.zip) (13.64 MB)

#### Chapter 10 - Improving Agents with the Perception System

* [Unreal Agility Arena - Chapter 10 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter10-end/unrealagilityarena-chapter-10-end.zip) (13.7 MB)

#### Chapter 11 - Understanding the Environment Query System

* [Unreal Agility Arena - Chapter 11 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter11-end/unrealagilityarena-chapter-11-end.zip) (13.72 MB)

### Part 4

#### Chapter 12 - Using Hierarchical State Machines with State Trees

* [Unreal Agility Arena - Chapter 12 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter-12-end/unrealagilityarena-chapter-12-end.zip) (13.60 MB)

#### Chapter 13 - Implementing Data-Oriented Calculations with Mass

* [Unreal Agility Arena - Chapter 13 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter-13-end/unrealagilityarena-chapter-13-end.zip) (38.69 MB)

#### Chapter 14 - Implementing Interactable Elements with Smart Objects

* [Unreal Agility Arena - Chapter 14 - End](https://github.com/PacktPublishing/Artificial-Intelligence-in-Unreal-Engine-5/releases/download/uaa-chapter-14-end/unrealagilityarena-chapter-14-end.zip) (13.78 MB)

## Credits

* **Models**
   * _KayKit Prototype Bits (1.0)_: created/distributed by [www.kaylousberg.com](http://www.kaylousberg.com)
   * _KayKit Space Base Bits (1.0)_: created/distributed by [www.kaylousberg.com](http://www.kaylousberg.com)
   
## Related products <Other books you may enjoy>
* Cinematic Photoreal Environments in Unreal Engine 5  [[Packt]](https://www.packtpub.com/en-us/product/cinematic-photoreal-environments-in-unreal-engine-5-9781803244112) [[Amazon]](https://www.amazon.com/Cinematic-Photoreal-Environments-Unreal-Engine/dp/1803244119)

* ​​Blueprints Visual Scripting for Unreal Engine 5  [[Packt]](https://www.packtpub.com/en-us/product/blueprints-visual-scripting-for-unreal-engine-5-9781801811583) [[Amazon]](https://www.amazon.com/Blueprints-Visual-Scripting-Unreal-Engine/dp/180181158X)

## Get to Know the Author
**Marco Secchi** is a freelance game developer who graduated in computer engineering at the Polytechnic
University of Milan. He is a lecturer and lead game advisor at Nuova Accademia di Belle Arti (NABA)
where he also mentors BA students in their final thesis projects. In his spare time, he reads a lot, plays
video games (less than he would like), and tries to practice CrossFit.
