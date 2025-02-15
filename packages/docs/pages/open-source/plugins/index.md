# Plugin system

Since the beginning of the project, Orama has been developed thinking of a simple way to add new features via a plugin system, leaving the core as small as possible.

As for `v2.0.0-beta.5`, Orama introduces the concept of **Plugins** in the core of the project, so that anyone could interact with the core operations of the search engine by providing their own custom features and plugins.

That said, the Orama core team is working on some official plugins to support specific features that might be useful for the general public. That way, you will be able to bring in only the features you really need.

All the official plugins' source code is hosted under the [Orama](https://github.com/oramasearch/orama) monorepo, in the [`packages`](https://github.com/oramasearch/orama/tree/main/packages) directory.

If you want to learn more about writing your own plugins, read the guide [available here](/open-source/plugins/writing-your-own-plugins).
