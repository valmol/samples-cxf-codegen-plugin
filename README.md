# Sample CXF Codegen Plugin

Apache CXF's wsdl2java support is pluggable. 
There is a META-INF/tools-plugin.xml descriptor that allows you to define custom generators ("frontend profiles"). 
Sample shows howto implement and use Service Endpoint Interface (SEI) generator. 
Custom generator extends the default one, but provides a different velocity template. 
This velocity template is identical to the default one, except that sample javadoc added for generated SEI.

Inspired by https://github.com/playframework/play-soap#wsdl2java

