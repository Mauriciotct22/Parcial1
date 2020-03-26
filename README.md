!DOCTYPE html>
<html>
<head>
	<title>Parcial-Practica</title>
	    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <header>
        <nav class="navegacion">
            <ul class="menu">
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Local</a></li>
                <li><a href="#">Contacto</a>
                </li>
            </ul>
        </nav>
    </header>
    <center>
        <center>Vision</center>

        <p>Consolidarnos en Centro America como la cadena lider en cocina mexicana
            distinguirnos de los demas restaurantes por nuestro ambiente familiar y agradable,
            servicio cordial, personalizado y precios accesibles, logrando asi la satisfaccion de nuestros consumidores.
        </p>

         <center>Mision</center>
         
           <p>Continuar siendo la cadena lider de restaurantes de cocina mexicana,
            en Centro America, mediante la estandarizacion y cumplimiento de los procedimientos y de los valores
            C.L.A.A.S.E.,
            cumpliendo asi las expectativas de nuestros clientes y logrando su lealtad hacia nuestra marca.
        </p>
    </center>


</body>
</html>





--------------------------------------------------------------------------------------------------------------------------------------
*{
	margin: 0;
	padding: 0;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
}

body{
	background:  #fff;
}

header{
	width: 100%;
}

.navegacion{
	width: 1300px;
	margin: 30px auto;
	background: #60C5F1;
}

.navegacion ul{
	list-style: none;
}

.menu > li{
	position: relative;
	display: inline-block;
}

.menu > li > a{
	display: block;
	padding: 10px 10px;
	color: #fff;
	font-family: 'Open sans';
	text-decoration: none;
}

.menu li a:hover{
	color: #CE7D35;
	transition: all .3s;
}

/* Submenu*/

.submenu{
	position: absolute;
	background: #333333;
	width: 120%;
	visibility: hidden;
	opacity: 0;
	transition: opacity 1.5s;
}

.submenu li a{
	display: block;
	padding: 15px;
	color: #fff;
	font-family: 'Open sans';
	text-decoration: none;
}

.menu li:hover .submenu{
	visibility: visible;
	opacity: 1;









-------------------------------------------------------------------------------------------------------------------------------------
<?xml version="1.0" encoding="UTF-8"?>

<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>

  <groupId>com.mm.Parcial-Practica</groupId>
  <artifactId>Parcial-Practica</artifactId>
  <version>0.0.1-SNAPSHOT</version>
  <packaging>war</packaging>

  <name>Parcial-Practica Maven Webapp</name>
  <!-- FIXME change it to the project's website -->
  <url>http://www.example.com</url>

  <properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
    <maven.compiler.source>1.7</maven.compiler.source>
    <maven.compiler.target>1.7</maven.compiler.target>
  </properties>

<dependencies>
<dependency>
<groupId>junit</groupId>
<artifactId>junit</artifactId>
<version>4.11</version>
<scope>test</scope>
</dependency>
<dependency>
<groupId>mysql</groupId>
<artifactId>mysql-connector-java</artifactId>
<version>5.1.47</version>
</dependency>
<dependency>
<groupId>org.hibernate</groupId>
<artifactId>hibernate-core</artifactId>
<version>5.2.17.Final</version>
</dependency>
<dependency>
<groupId>javax.servlet</groupId>
<artifactId>javax.servlet-api</artifactId>
<version>3.1.0</version>
</dependency>
</dependencies>

  <build>
    <finalName>Parcial-Practica</finalName>
    <pluginManagement><!-- lock down plugins versions to avoid using Maven defaults (may be moved to parent pom) -->
      <plugins>
        <plugin>
          <artifactId>maven-clean-plugin</artifactId>
          <version>3.1.0</version>
        </plugin>
        <!-- see http://maven.apache.org/ref/current/maven-core/default-bindings.html#Plugin_bindings_for_war_packaging -->
        <plugin>
          <artifactId>maven-resources-plugin</artifactId>
          <version>3.0.2</version>
        </plugin>
        <plugin>
          <artifactId>maven-compiler-plugin</artifactId>
          <version>3.8.0</version>
        </plugin>
        <plugin>
          <artifactId>maven-surefire-plugin</artifactId>
          <version>2.22.1</version>
        </plugin>
        <plugin>
          <artifactId>maven-war-plugin</artifactId>
          <version>3.2.2</version>
        </plugin>
        <plugin>
          <artifactId>maven-install-plugin</artifactId>
          <version>2.5.2</version>
        </plugin>
        <plugin>
          <artifactId>maven-deploy-plugin</artifactId>
          <version>2.8.2</version>
        </plugin>
      </plugins>
    </pluginManagement>
  </build>
</project>







































