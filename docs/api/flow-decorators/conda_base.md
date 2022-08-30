# @conda_base

The `@conda_base` decorator specifies what libraries should be made available for all steps of a flow.

The libraries are installed from [Conda repositories](https://anaconda.org/). For more information, see [Managing External Libraries](/metaflow/dependencies).

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! Instead, edit the notebook w/the location & name as this file. -->


<DocSection type="decorator" name="conda_base" module="metaflow" show_import="True" heading_level="3" link="https://github.com/Netflix/metaflow/tree/master/metaflow/plugins/conda/conda_flow_decorator.py#L5">
<SigArgSection>
<SigArg name="..." />
</SigArgSection>
<Description summary="Specifies the Conda environment for all steps of the flow." extended_summary="Use `@conda_base` to set common libraries required by all\nsteps and use `@conda` to specify step-specific additions." />
<ParamSection name="Parameters">
	<Parameter name="libraries" type="Dict" desc="Libraries to use for this flow. The key is the name of the package\nand the value is the version to use (Default: {})." />
	<Parameter name="python" type="string" desc="Version of Python to use, e.g. '3.7.4'\n(Default: None, i.e. the current Python version)." />
	<Parameter name="disabled" type="bool" desc="If set to True, disables Conda (Default: False)." />
</ParamSection>
</DocSection>
