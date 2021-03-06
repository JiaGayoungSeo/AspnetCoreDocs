

ConfigurationSection Class
==========================



.. contents:: 
   :local:







Inheritance Hierarchy
---------------------


* :dn:cls:`System.Object`
* :dn:cls:`Microsoft.Extensions.Configuration.ConfigurationSection`








Syntax
------

.. code-block:: csharp

   public class ConfigurationSection : IConfigurationSection, IConfiguration





GitHub
------

`View on GitHub <https://github.com/aspnet/configuration/blob/master/src/Microsoft.Extensions.Configuration/ConfigurationSection.cs>`_





.. dn:class:: Microsoft.Extensions.Configuration.ConfigurationSection

Constructors
------------

.. dn:class:: Microsoft.Extensions.Configuration.ConfigurationSection
    :noindex:
    :hidden:

    
    .. dn:constructor:: Microsoft.Extensions.Configuration.ConfigurationSection.ConfigurationSection(Microsoft.Extensions.Configuration.ConfigurationRoot, System.String)
    
        
        
        
        :type root: Microsoft.Extensions.Configuration.ConfigurationRoot
        
        
        :type path: System.String
    
        
        .. code-block:: csharp
    
           public ConfigurationSection(ConfigurationRoot root, string path)
    

Methods
-------

.. dn:class:: Microsoft.Extensions.Configuration.ConfigurationSection
    :noindex:
    :hidden:

    
    .. dn:method:: Microsoft.Extensions.Configuration.ConfigurationSection.GetChildren()
    
        
        :rtype: System.Collections.Generic.IEnumerable{Microsoft.Extensions.Configuration.IConfigurationSection}
    
        
        .. code-block:: csharp
    
           public IEnumerable<IConfigurationSection> GetChildren()
    
    .. dn:method:: Microsoft.Extensions.Configuration.ConfigurationSection.GetReloadToken()
    
        
        :rtype: Microsoft.Extensions.Primitives.IChangeToken
    
        
        .. code-block:: csharp
    
           public IChangeToken GetReloadToken()
    
    .. dn:method:: Microsoft.Extensions.Configuration.ConfigurationSection.GetSection(System.String)
    
        
        
        
        :type key: System.String
        :rtype: Microsoft.Extensions.Configuration.IConfigurationSection
    
        
        .. code-block:: csharp
    
           public IConfigurationSection GetSection(string key)
    

Properties
----------

.. dn:class:: Microsoft.Extensions.Configuration.ConfigurationSection
    :noindex:
    :hidden:

    
    .. dn:property:: Microsoft.Extensions.Configuration.ConfigurationSection.Item[System.String]
    
        
        
        
        :type key: System.String
        :rtype: System.String
    
        
        .. code-block:: csharp
    
           public string this[string key] { get; set; }
    
    .. dn:property:: Microsoft.Extensions.Configuration.ConfigurationSection.Key
    
        
        :rtype: System.String
    
        
        .. code-block:: csharp
    
           public string Key { get; }
    
    .. dn:property:: Microsoft.Extensions.Configuration.ConfigurationSection.Path
    
        
        :rtype: System.String
    
        
        .. code-block:: csharp
    
           public string Path { get; }
    
    .. dn:property:: Microsoft.Extensions.Configuration.ConfigurationSection.Value
    
        
        :rtype: System.String
    
        
        .. code-block:: csharp
    
           public string Value { get; set; }
    

