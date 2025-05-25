# kedro-snap

Experiment in packaging Kedro as a Snap.

> [!WARNING]
> Note that `kedro run` will need to import your pipelines,
> and this will likely fail the moment you need specific dependencies
> or a Python version different than the one used in the Snap.
> For this reason and to avoid confusion the Snap will not be published,
> it is shown here for demonstration and learning purposes.
