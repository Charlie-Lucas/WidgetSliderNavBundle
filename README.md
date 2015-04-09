Victoire CMS SliderNav Bundle
============

Need to add a slidernav in a victoire cms website ?
Get this slidernav bundle and so on

First you need to have a valid Symfony2 Victoire edition.
Then you just have to run the following composer command :

    php composer.phar require victoire/slidernav-widget

Do not forget to add the bundle in your AppKernel !

    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                ...
                new Victoire\Widget\SliderNavBundle\VictoireWidgetSliderNavBundle(),
            );

            return $bundles;
        }
    }

[![Licence Creative Commons](http://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

This product is provided under [Licence Creative Commns Attributions - No commercial use - No share 4.0 France](http://creativecommons.org/licenses/by-nc-nd/4.0/fr/) terms.
