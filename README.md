required_parts = {"xyz1", "xyz2", "xyz3", "xyz4", "xyz5"}
is_completed = False
name = " "
while not is_completed:
     print("Podaj nazwę przedmiotu: \n")
     part_name = input()
     for part in required_parts:
     
         if (part_name == part): 
             required_parts.remove(part);
             print("Znaleziona czesc\n")
             break;
         
     
     if (not required_parts):
         is_completed = True;
         print("Mission complete!")
