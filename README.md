# solar-system-
SOLAR SYSTEM WITH WEB VPYTHON 
from vpython import *
earth= sphere(pos=vector(-130,0,-80),
radius=1.8,
texture=textures.earth, make_trail =True , trail_radius= 0.1)
earth_label= label( pos=vector(-130,0,-80), text='Earth', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')
earth_label2= label( pos=vector(-130,0,-80), text="Age: Earth is about 4.54 billion years old.", xoffset=70, yoffset=60, space=20, height=10, border=10, font='sans')
earth_label3= label( pos=vector(-130,0,-80), text="Shape: It’s not a perfect sphere — it’s an oblate spheroid, slightly squished at the poles.", xoffset=70, yoffset=75, space=20, height=10, border=10, font='sans')
earth_label4= label( pos=vector(-130,0,-80), text="Oceans: About 71% of Earth’s surface is covered in water, mostly oceans", xoffset=70, yoffset=100, space=20, height=10, border=10, font='sans')
earth_label5= label( pos=vector(-130,0,-80), text="Atmosphere: Made mostly of nitrogen (78%) and oxygen (21%).", xoffset=70, yoffset=125, space=20, height=10, border=10, font='sans')



moon = sphere(texture=textures.metal
,pos= vector(-19,0,7)
,radius=0.6 ,
size =vector(9,5,5),make_trail= False ,trail_radius= 0.1 )

mercury = sphere(texture= (r'https://assets.science.nasa.gov/dynamicimage/assets/science/psd/solar/2023/09/p/i/a/1/PIA17386.jpg?w=4096&h=2048&fit=clip&crop=faces%2Cfocalpoint'),
radius=0.8,
pos= vector(-50,0,17),make_trail=True ,trail_radius= 0.1 )
mercury_label= label( pos=vector(-50,0,17), text='Mercury ', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')
mercury_label2= label( pos=vector(-50,0,17), text='Closest planet to the Sun. ', xoffset=70, yoffset=10, space=20, height=10, border=4, font='sans')
mercury_label3= label( pos=vector(-50,0,17), text=' Extreme temperatures: 430°C in the day, –180°C at night.', xoffset=95, yoffset=25, space=30, height=10, border=4, font='sans')
mercury_label4= label( pos=vector(-50,0,17), text='Has no atmosphere to trap heat.', xoffset=95, yoffset=40, space=30, height=10, border=4, font='sans')
mercury_label5= label( pos=vector(-50,0,17), text='A year on Mercury = 88 Earth days.', xoffset=95, yoffset=55, space=30, height=10, border=4, font='sans')
mercury_label6= label( pos=vector(-50,0,17), text='Smallest planet in the Solar System..', xoffset=95, yoffset=70, space=30, height=10, border=4, font='sans')


venus = sphere(texture= (r'https://upload.wikimedia.org/wikipedia/commons/6/63/Solarsystemscope_texture_2k_venus_atmosphere.jpg'),
radius=1,
pos= vector(-100,0,12) ,make_trail=True ,trail_radius= 0.1 )
venus_label= label( pos=vector(-100,0,12), text='Venus', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')
venus_label2= label( pos=vector(-100,0,12), text='Hottest planet: surface temp ~475°C (hotter than Mercury).', xoffset=70, yoffset=10, space=30, height=10, border=4, font='sans')
venus_label3= label( pos=vector(-100,0,12), text='Thick atmosphere made mostly of CO₂, with clouds of sulfuric acid.', xoffset=95, yoffset=25, space=30, height=10, border=4, font='sans')
venus_label4= label( pos=vector(-100,0,12), text='Rotates backwards, so the Sun rises in the west.', xoffset=95, yoffset=40, space=30, height=10, border=4, font='sans')
venus_label5= label( pos=vector(-100,0,12), text='Similar size to Earth — called Earth’s “sister planet.”', xoffset=95, yoffset=55, space=30, height=10, border=4, font='sans')



jupiter= sphere(texture=(r'https://upload.wikimedia.org/wikipedia/commons/b/be/Solarsystemscope_texture_2k_jupiter.jpg'),radius= 5,
pos= vector(-400 , 0 , -280),make_trail= True , trail_radius= 0.1)
jupiter_label= label( pos=vector(-400,0,-280), text='Jupiter', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')
jupiter_label2= label( pos=vector(-400,0,-280), text='Largest planet in the Solar System.', xoffset=70, yoffset=10, space=30, height=10, border=4, font='sans')
jupiter_label3= label( pos=vector(-400,0,-280), text='A gas giant made of hydrogen and helium.', xoffset=95, yoffset=25, space=30, height=10, border=4, font='sans')
jupiter_label4= label( pos=vector(-400,0,-280), text='Has the Great Red Spot, a storm bigger than Earth.', xoffset=95, yoffset=40, space=30, height=10, border=4, font='sans')
jupiter_label5= label( pos=vector(-400,0,-280), text='Insanely strong magnetic field.', xoffset=95, yoffset=70, space=30, height=10, border=4, font='sans')


sun = sphere(texture= (r'https://upload.wikimedia.org/wikipedia/commons/9/99/Map_of_the_full_sun.jpg'),
radius=8,
pos= vector(0,0,17))
son_lable= label( pos=vector(0,0,17), text='Son', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')

mars = sphere(texture= (r'https://upload.wikimedia.org/wikipedia/commons/7/70/Solarsystemscope_texture_8k_mars.jpg' ),
radius= 3 ,
pos = vector (-250,0,-150 ), make_trail= True , trail_radius= 0.1)
mars_label= label( pos=vector(-250 ,0,-150), text='Mars', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')
mars_label2= label( pos=vector(-250 ,0,-150), text='Known as the Red Planet (iron oxide in the soil).', xoffset=70, yoffset=10, space=30, height=10, border=4, font='sans')
mars_label3= label( pos=vector(-250 ,0,-150), text='Has the largest volcano in the Solar System: Olympus Mons.', xoffset=95, yoffset=25, space=30, height=10, border=4, font='sans')
mars_label4= label( pos=vector(-250 ,0,-150), text='Thin CO₂ atmosphere.', xoffset=95, yoffset=40, space=30, height=10, border=4, font='sans')
mars_label5= label( pos=vector(-250 ,0,-150), text='Signs of ancient water — once had rivers and lakes.', xoffset=95, yoffset=70, space=30, height=19, border=4, font='sans')


uranus=sphere(texture=(r'https://upload.wikimedia.org/wikipedia/commons/9/95/Solarsystemscope_texture_2k_uranus.jpg'),radius= 4.5, pos= vector(-1200 ,0 , 780),make_trail= True , trail_radius= 0.1 )
uranus_label= label( pos=vector(-1200,0,780), text='Uranus', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')
uranus_label2= label( pos=vector(-1200,0,780), text='An ice giant with lots of methane giving it a blue color.', xoffset=70, yoffset=10, space=30, height=10, border=4, font='sans')
uranus_label3= label( pos=vector(-1200,0,780), text='Rotates on its side — tilted 98°, like it’s rolling around the Sun.', xoffset=95, yoffset=25, space=30, height=10, border=4, font='sans')
uranus_label4= label( pos=vector(-1200,0,780), text='Extremely cold: down to –224°C.', xoffset=95, yoffset=40, space=30, height=10, border=4, font='sans')
uranus_label5= label( pos=vector(-1200,0,780), text='Faint ring system', xoffset=95, yoffset=70, space=30, height=10, border=4, font='sans')



neptune=sphere(texture=(r'https://upload.wikimedia.org/wikipedia/commons/1/1e/Solarsystemscope_texture_2k_neptune.jpg'),radius=4, pos = vector(-2200 ,0 , 780),make_trail= True , trail_radius= 0.1)
neptune_label=label( pos=vector(-2200,0,780), text='Neptune', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')
neptune_label2=label( pos=vector(-2200,0,780), text='Farthest major planet from the Sun.', xoffset=70, yoffset=10, space=30, height=10, border=4, font='sans')
neptune_label3=label( pos=vector(-2200,0,780), text='Ice giant with deep blue color', xoffset=95, yoffset=25, space=30, height=10, border=4, font='sans')
neptune_label4=label( pos=vector(-2200,0,780), text='Strongest winds in the Solar System, over 2,000 km/h.', xoffset=95, yoffset=40, space=30, height=10, border=4, font='sans')
neptune_label5=label( pos=vector(-2200,0,780), text='Has a dark storm similar to Jupiter’s Great Red Spot', xoffset=95, yoffset=70, space=30, height=10, border=4, font='sans')

saturn=sphere(texture= (r'https://upload.wikimedia.org/wikipedia/commons/5/5e/Solarsystemscope_texture_8k_jupiter.jpg'),radius = 6 , pos= vector(-700 , 0 , 780 ),make_trail= True , trail_radius= 0.1)
saturn_lable= label( pos=vector(-700,0,780), text='Saturn', xoffset=20, yoffset=50, space=30, height=16, border=4, font='sans')
saturn_lable2= label( pos=vector(-700,0,780), text='Famous for its massive, bright ring system made of ice and rock.', xoffset=70, yoffset=10, space=30, height=10, border=4, font='sans')
saturn_lable3= label( pos=vector(-700,0,780), text='Second-largest planet.', xoffset=95, yoffset=25, space=30, height=10, border=4, font='sans')
saturn_lable4= label( pos=vector(-700,0,780), text='Gas giant like Jupiter.', xoffset=95, yoffset=40, space=30, height=10, border=4, font='sans')
saturn_lable5= label( pos=vector(-700,0,780), text='Has over 140 moons, including Titan, which has lakes of liquid methane.', xoffset=95, yoffset=70, space=30, height=10, border=4, font='sans')


saturn_ring1=ring(pos=vec(-700, 0, 780 ), axis=vec(-5, 50,0), radius = 10, thickness = 0.01 ,texture= ('https://upload.wikimedia.org/wikipedia/commons/7/7d/Solarsystemscope_texture_2k_saturn_ring_alpha.png'))
saturn_ring2=ring(pos=vec(-700, 0, 780 ), axis=vec(-5, 50,0), radius = 10.5, thickness = 0.01 ,texture= ('https://upload.wikimedia.org/wikipedia/commons/7/7d/Solarsystemscope_texture_2k_saturn_ring_alpha.png'))
saturn_ring3=ring(pos=vec(-700, 0,780 ), axis=vec(-5, 50,0), radius = 11, thickness = 0.01 ,texture= ('https://upload.wikimedia.org/wikipedia/commons/7/7d/Solarsystemscope_texture_2k_saturn_ring_alpha.png'))
saturn_ring4=ring(pos=vec(-700, 0, 780 ), axis=vec(-5, 50,0), radius = 11.5, thickness = 0.1 ,texture= ('https://upload.wikimedia.org/wikipedia/commons/7/7d/Solarsystemscope_texture_2k_saturn_ring_alpha.png'))
saturn_ring5=ring(pos=vec(-700, 0, 780 ), axis=vec(-5, 50,0), radius = 12, thickness = 0.1 ,texture= ('https://upload.wikimedia.org/wikipedia/commons/7/7d/Solarsystemscope_texture_2k_saturn_ring_alpha.png'))
saturn_ring6=ring(pos=vec(-700, 0, 780), axis=vec(-5, 50,0), radius = 12.5, thickness = 0.3 ,texture= ('https://upload.wikimedia.org/wikipedia/commons/7/7d/Solarsystemscope_texture_2k_saturn_ring_alpha.png'))
saturn_ring7=ring(pos=vec(-700, 0, 780), axis=vec(-5, 50,0), radius = 13, thickness = 0.3 ,texture= ('https://upload.wikimedia.org/wikipedia/commons/7/7d/Solarsystemscope_texture_2k_saturn_ring_alpha.png'))

mercury_solar_rotation =2*3.141592653589793/88

earths_solar_rotation= 2* 3.141592653589793/365
 
earth_lable_rotation = 2* 3.141592653589793/365

mars_solar_rotation= 2* 3.141592653589793 / 687

venus_solar_rotation= 2* 3.141592653589793/225

jupiters_solar_raotation= 2*3.141592653589793/4333

saturn_solar_rotation= 2 * 3.141592653589793/10759

saturn_rings_rotation= 2 * 3.141592653589793/10759

uranius_solar_rotation= 2 * 3.141592653589793/30687

neptune_solar_rotation= 2 * 3.141592653589793/ 60190

moonAngle=0
moons_earth_rotation = 2 * 3.141592653589793 / 27
paused = False

def toggle_pause(evt):
    global paused
    paused = not paused   

scene.bind('mousedown', toggle_pause)
while True:
 rate(30)
 if not paused :
  neptune.rotate(angle=neptune_solar_rotation, axis=vector(0,500,0),origin= vector(0,0,17))
  neptune_label.rotate(angle=neptune_solar_rotation, axis=vector(0,500,0),origin= vector(0,0,17 ))
  neptune_label2.rotate(angle=neptune_solar_rotation, axis=vector(0,500,0),origin= vector(0,0,17 ))
  neptune_label3.rotate(angle=neptune_solar_rotation, axis=vector(0,500,0),origin= vector(0,0,17 ))
  neptune_label4.rotate(angle=neptune_solar_rotation, axis=vector(0,500,0),origin= vector(0,0,17 ))
  neptune_label5.rotate(angle=neptune_solar_rotation, axis=vector(0,500,0),origin= vector(0,0,17 ))


  uranus.rotate(angle=uranius_solar_rotation, axis=vector(0,350,0),origin= vector(0,0,17))
  uranus_label.rotate(angle=uranius_solar_rotation, axis=vector(0,350,0),origin= vector(0,0,17))
  uranus_label2.rotate(angle=uranius_solar_rotation, axis=vector(0,350,0),origin= vector(0,0,17))
  uranus_label3.rotate(angle=uranius_solar_rotation, axis=vector(0,350,0),origin= vector(0,0,17))
  uranus_label4.rotate(angle=uranius_solar_rotation, axis=vector(0,350,0),origin= vector(0,0,17))
  uranus_label5.rotate(angle=uranius_solar_rotation, axis=vector(0,350,0),origin= vector(0,0,17))


  mercury.rotate(angle= mercury_solar_rotation,axis= vector(0,30,0),origin=vector(0,0,17))
  mercury_label.rotate(angle= mercury_solar_rotation,axis= vector(0,30,0),origin=vector(0,0,17))
  mercury_label2.rotate(angle= mercury_solar_rotation,axis= vector(0,30,0),origin=vector(0,0,17))
  mercury_label3.rotate(angle= mercury_solar_rotation,axis= vector(0,30,0),origin=vector(0,0,17))
  mercury_label4.rotate(angle= mercury_solar_rotation,axis= vector(0,30,0),origin=vector(0,0,17))
  mercury_label5.rotate(angle= mercury_solar_rotation,axis= vector(0,30,0),origin=vector(0,0,17))
  mercury_label6.rotate(angle= mercury_solar_rotation,axis= vector(0,30,0),origin=vector(0,0,17))



  earth.rotate(angle = earths_solar_rotation, axis=vector(0,10,0) ,origin=vector(0,0,17))
  earth_label.rotate(angle=earth_lable_rotation,axis=vector(0,10,0) ,origin=vector(0,0,17))  
  earth_label2.rotate(angle=earth_lable_rotation,axis=vector(0,10,0) ,origin=vector(0,0,17))
  earth_label3.rotate(angle=earth_lable_rotation,axis=vector(0,10,0) ,origin=vector(0,0,17))
  earth_label4.rotate(angle=earth_lable_rotation,axis=vector(0,10,0) ,origin=vector(0,0,17))
  earth_label5.rotate(angle=earth_lable_rotation,axis=vector(0,10,0) ,origin=vector(0,0,17))
  


  mars.rotate (angle=mars_solar_rotation,axis=vector(0,50,0), origin=vector(0,0,17) )
  mars_label.rotate(angle=mars_solar_rotation,axis=vector(0,50,0), origin=vector(0,0,17) )
  mars_label2.rotate(angle=mars_solar_rotation,axis=vector(0,50,0), origin=vector(0,0,17) )
  mars_label3.rotate(angle=mars_solar_rotation,axis=vector(0,50,0), origin=vector(0,0,17) )
  mars_label4.rotate(angle=mars_solar_rotation,axis=vector(0,50,0), origin=vector(0,0,17) )
  mars_label5.rotate(angle=mars_solar_rotation,axis=vector(0,50,0), origin=vector(0,0,17) )

  jupiter.rotate(angle= jupiters_solar_raotation,axis= vector(0,50,0), origin= vector(0,0,17) )
  jupiter_label.rotate(angle= jupiters_solar_raotation,axis= vector(0,50,0), origin= vector(0,0,17) )
  jupiter_label2.rotate(angle= jupiters_solar_raotation,axis= vector(0,50,0), origin= vector(0,0,17) )
  jupiter_label3.rotate(angle= jupiters_solar_raotation,axis= vector(0,50,0), origin= vector(0,0,17) )
  jupiter_label4.rotate(angle= jupiters_solar_raotation,axis= vector(0,50,0), origin= vector(0,0,17) )
  jupiter_label5.rotate(angle= jupiters_solar_raotation,axis= vector(0,50,0), origin= vector(0,0,17) )

  venus.rotate (angle=venus_solar_rotation,axis=vector(0,30,0), origin=vector(0,0,17))
  venus_label.rotate(angle=venus_solar_rotation,axis=vector(0,30,0),origin=vector(0,0,17))
  venus_label2.rotate(angle=venus_solar_rotation,axis=vector(0,30,0),origin=vector(0,0,17))
  venus_label3.rotate(angle=venus_solar_rotation,axis=vector(0,30,0),origin=vector(0,0,17))
  venus_label4.rotate(angle=venus_solar_rotation,axis=vector(0,30,0),origin=vector(0,0,17))
  venus_label5.rotate(angle=venus_solar_rotation,axis=vector(0,30,0),origin=vector(0,0,17))

  saturn.rotate(angle=saturn_solar_rotation,axis=vector(0,100,0),origin=vector(0,0,17))
  saturn_lable.rotate(angle=saturn_solar_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_lable2.rotate(angle=saturn_solar_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_lable3.rotate(angle=saturn_solar_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17)) 
  saturn_lable4.rotate(angle=saturn_solar_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_lable5.rotate(angle=saturn_solar_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_ring1.rotate(angle=saturn_rings_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_ring2.rotate(angle=saturn_rings_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_ring3.rotate(angle=saturn_rings_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_ring4.rotate(angle=saturn_rings_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_ring5.rotate(angle=saturn_rings_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_ring6.rotate(angle=saturn_rings_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))
  saturn_ring7.rotate(angle=saturn_rings_rotation, axis = vector(0,250,0 ),origin= vector(0,0,17))

  moonAngle+=moons_earth_rotation
  moon.pos=earth.pos + vector(7,0,0)
  moon.rotate(angle=moonAngle, axis=vector(0,1,0), origin=earth.pos)
