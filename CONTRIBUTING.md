To contribute to this repository please follow these guidelines:

1. Use a unique ID for every asset you introduce. For Keywords, categories etc. this is always an auto generated hash, but for functional asset you should provide an own unique ID that reflects the source
2. You can use a reverse domain name for this like de.bonkers.neutron.asset.myassetname where the domain used should be connected to you personally. 
3. If you do not have one, or do not want to use it, please use com.github.bmarl.neutron.myassetname. The use of an individual domain is preferred

To be able to define an own asset ID you will need to add the following option to either ressource\config.txt or as a commandline argument g_newAssetPrefix=myassetdomain.
As an example, the 3D Noise asset was created with "de.bonkers.neutron.asset." as the value for g_newAssetPrefix. 
This will make sure that what ever name you give your asset will not collide with the name of any other asset created by other contributors, or Maxon.

Under NO CIRCUMSTANCES use the Maxon domain used by the assets that come with Cinema 4D. Assets contributed with such IDs will be removed.

General information on the creation of assets can be found in the Cinema 4D documentation and other Maxon information sources. 
