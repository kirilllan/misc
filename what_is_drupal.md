  
  Drupal is a free, open-source Content Management System and content management framework. It is tailorable and customizable web-app that gives user(s) ability for creating, updating and managing access. 
  
  Drupal uses PHP: Hypertext pre-processor as its programming language. Drupal accessible, flexible, movable, scalable and has 40 000+ of free modules that extend site functionality and 2 500+ themes that modify sites appearance. It is used by over one million websites. Additional reasons to use Drupal: it is easier, quicker, cheaper and has many options.
  
  Drupal uses data serialization format YAML. YAML means “YAML ain’t markup language”. In Drupal YAML is used for storing meta-data about projects in “mymodule.info.yml”, storing configuration data, routing, service declaration, permissions. YAML is parsed by “Drupal\Component\Serialization\Yaml”.
  
  Drupal uses Twig as its default template engine. When you will be wanting to make changes to markup that Drupal outputs you will need to know some Twig. Drupal adopted Twig instead of PHP template for numerous reasons: improved security by sanitizing HTML code and not executing PHP code plus simpler and cleaner templates.  Twig is supported broadly inside of Drupal community and adopted widely outside of it.

If one wants to go deeper with Drupal, understanding how information flows between the system’s layers is needed. Five main layers to consider are: 
1)	Data (nodes)
2)	Modules
3)	Blocks & Menus
4)	User permissions
5)	Template

  1 – At the base of the Drupal system is the data pool; collection of nodes. It must be an input as data, before anything can be displayed on the site.

  2 – This is the layer where functional plugins called modules live. They allow you to customize the data items on your node types and programmatically sort and display content.

  3 – Blocks can be created to display whatever wanted and then be placed in your template (theme) layout. Menus provide links to all pages.

  4 – Permissions define what users are allowed to do and see.

  5 – Top layer is “the skin”; site theme made mostly of XHTML and CSS with possible Twig variables.
