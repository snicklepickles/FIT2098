![[Design Considerations-20250312220207674.png]]
## Mixed Reality
### Frame Rate
- 90 FPS minimum for VR
- 60 FPS is ok for AR
- Loss of realism
- Major cause of “simulator sickness”
### Style
- Degree of realism: photorealistic ←→ cartoon-like
- Can use stylised low-poly models
	- E.g., Minecraft
- Keep style **consistent**
### Scale
- Object size is relative to human scale
- 1 Unity unit = 1 metre
### Tracker Marker Visibility
- Occlusion (e.g., hand blocking marker)
- Relative angle
- Camera range
![[Design Considerations-20250312220756154.png|442]]
## Augmented Reality
![[Design Considerations-20250312221623837.png]]
### Direct Manipulation
- Users act on displayed objects of interest using *physical, incremental, reversible* actions whose effects are *immediately* visible on the screen
- **Advantages:**
	- Reflects real world interactions
	- Intuitive, easy to learn
	- Visibility and discoverability
- **Disadvantages:**
	- Slow
	- Gestures can be error prone
	- Not good for repetitive actions
	- Accessibility may suffer
![[Design Considerations-20250312222206236.png]]
- **Benefit:** Ease of access
- **Limits:**
	- Graphical complexity
	- Real-time interactions
	- Narrow display, aspect ratio