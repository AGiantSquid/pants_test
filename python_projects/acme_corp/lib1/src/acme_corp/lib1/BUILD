python_sources()

pex_binary(
  name="lib1_pex",
  entry_point="lib1_module1.py:lib1_func1"
)

python_distribution(
    name="lib1_dist",
    dependencies=[
        'python_projects/acme_corp/lib1/src/acme_corp/lib1',
    ],
    sdist=True,
    provides=python_artifact(
        name="acme_corp.lib1",
        version="0.0.0",
    ),
)
