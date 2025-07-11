# python-stars
celestial_objects = {'Sirius':25, # Sirius is one of the brightest stars in the night sky
                     'Andromeda Galaxy':1000000, # Andromeda Galaxy has a very high luminosity
                     'Jupiter':0.00006,# Jupiter reflects sunlight but has low intrinsic luminosity
                     'Pleiades':100,# The Pleiades star cluster is moderately luminous
                     'Orion Nebula':10000} # The Orion Nebula is a bright emission nebula
                    }
for objects in celestial_objects:
    print(objects)

for objects in celestial_objects.items():
    print(objects[0] + ":", objects[1], "solar units")

luminosities = []

for obj in celestial_objects.items():
    luminosities.append(obj[1])
                     
