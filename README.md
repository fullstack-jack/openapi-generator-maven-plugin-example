# Example bug with OpenAPI Maven Generator

I would expect `mvn generate-sources` to succeed, but it doesn't without the <inputSpec> parameter in the pom.xml, even though it's ignored.