workspace(name = "gitiles")

load("//tools:bazlets.bzl", "load_bazlets")

load_bazlets(
    commit = "a8bf43a97a2a655752204811d1355b180b082047",
    # local_path = "/home/<user>/projects/bazlets",
)

load(
    "@com_googlesource_gerrit_bazlets//tools:maven_jar.bzl",
    "GERRIT",
    "MAVEN_CENTRAL",
    "maven_jar",
)

maven_jar(
    name = "commons_lang3",
    artifact = "org.apache.commons:commons-lang3:3.6",
    sha1 = "9d28a6b23650e8a7e9063c04588ace6cf7012c17",
)

maven_jar(
    name = "commons_text",
    artifact = "org.apache.commons:commons-text:1.2",
    sha1 = "74acdec7237f576c4803fff0c1008ab8a3808b2b",
)

maven_jar(
    name = "gson",
    artifact = "com.google.code.gson:gson:2.8.4",
    sha1 = "d0de1ca9b69e69d1d497ee3c6009d015f64dad57",
)

maven_jar(
    name = "guava",
    artifact = "com.google.guava:guava:25.1-jre",
    sha1 = "6c57e4b22b44e89e548b5c9f70f0c45fe10fb0b4",
)

maven_jar(
    name = "jsr305",
    artifact = "com.google.code.findbugs:jsr305:3.0.0",
    attach_source = False,
    sha1 = "5871fb60dc68d67da54a663c3fd636a10a532948",
)

maven_jar(
    name = "prettify",
    artifact = "com.github.twalcari:java-prettify:1.2.2",
    sha1 = "b8ba1c1eb8b2e45cfd465d01218c6060e887572e",
)

COMMONMARK_VERSION = "0.10.0"

# When upgrading commonmark it should also be updated in plugins/gitiles
maven_jar(
    name = "commonmark",
    artifact = "com.atlassian.commonmark:commonmark:" + COMMONMARK_VERSION,
    sha1 = "119cb7bedc3570d9ecb64ec69ab7686b5c20559b",
)

maven_jar(
    name = "cm_autolink",
    artifact = "com.atlassian.commonmark:commonmark-ext-autolink:" + COMMONMARK_VERSION,
    sha1 = "a6056a5efbd68f57d420bc51bbc54b28a5d3c56b",
)

maven_jar(
    name = "autolink",
    artifact = "org.nibor.autolink:autolink:0.7.0",
    sha1 = "649f9f13422cf50c926febe6035662ae25dc89b2",
)

maven_jar(
    name = "gfm_strikethrough",
    artifact = "com.atlassian.commonmark:commonmark-ext-gfm-strikethrough:" + COMMONMARK_VERSION,
    sha1 = "40837da951b421b545edddac57012e15fcc9e63c",
)

maven_jar(
    name = "gfm_tables",
    artifact = "com.atlassian.commonmark:commonmark-ext-gfm-tables:" + COMMONMARK_VERSION,
    sha1 = "c075db2a3301100cf70c7dced8ecf86b494458a2",
)

maven_jar(
    name = "servlet_api_2_5",
    artifact = "org.eclipse.jetty.orbit:javax.servlet:2.5.0.v201103041518",
    sha1 = "9c16011c06bc6fe5e9dba080fcb40ddb4b75dc85",
)

maven_jar(
    name = "servlet_api_3_0",
    artifact = "org.eclipse.jetty.orbit:javax.servlet:3.0.0.v201112011016",
    sha1 = "0aaaa85845fb5c59da00193f06b8e5278d8bf3f8",
)

maven_jar(
    name = "truth",
    artifact = "com.google.truth:truth:0.40",
    sha1 = "0d74e716afec045cc4a178dbbfde2a8314ae5574",
)

maven_jar(
    name = "soy",
    artifact = "com.google.template:soy:2018-03-14",
    sha1 = "76a1322705ba5a6d6329ee26e7387417725ce4b3",
)

maven_jar(
    name = "html_types",
    artifact = "com.google.common.html.types:types:1.0.4",
    sha1 = "2adf4c8bfccc0ff7346f9186ac5aa57d829ad065",
)

maven_jar(
    name = "protobuf",
    artifact = "com.google.protobuf:protobuf-java:3.5.1",
    sha1 = "8c3492f7662fa1cbf8ca76a0f5eb1146f7725acd",
)

maven_jar(
    name = "icu4j",
    artifact = "com.ibm.icu:icu4j:57.1",
    sha1 = "198ea005f41219f038f4291f0b0e9f3259730e92",
)

JGIT_VERS = "5.0.1.201806211838-r"

JGIT_REPO = MAVEN_CENTRAL

maven_jar(
    name = "jgit_lib",
    artifact = "org.eclipse.jgit:org.eclipse.jgit:" + JGIT_VERS,
    repository = JGIT_REPO,
    sha1 = "dbba66a425d2153ccd749d0ba9c075b0ba424655",
)

maven_jar(
    name = "jgit_servlet",
    artifact = "org.eclipse.jgit:org.eclipse.jgit.http.server:" + JGIT_VERS,
    repository = JGIT_REPO,
    sha1 = "5d9cd43e880d49f14501ac48d59b55905f4ec5bf",
)

maven_jar(
    name = "jgit_junit",
    artifact = "org.eclipse.jgit:org.eclipse.jgit.junit:" + JGIT_VERS,
    repository = JGIT_REPO,
    sha1 = "f848735061fab81f2863f68cca8d533ff403c765",
)

maven_jar(
    name = "jgit_archive",
    artifact = "org.eclipse.jgit:org.eclipse.jgit.archive:" + JGIT_VERS,
    repository = JGIT_REPO,
    sha1 = "1d94e2bfa505dd719f62cfb036295022543af17e",
)

maven_jar(
    name = "ewah",
    artifact = "com.googlecode.javaewah:JavaEWAH:1.1.6",
    sha1 = "94ad16d728b374d65bd897625f3fbb3da223a2b6",
)

# When upgrading commons_compress, upgrade tukaani_xz to the
# corresponding version
maven_jar(
    name = "commons_compress",
    artifact = "org.apache.commons:commons-compress:1.15",
    sha1 = "b686cd04abaef1ea7bc5e143c080563668eec17e",
)

# Transitive dependency of commons_compress. Should only be
# upgraded at the same time as commons_compress.
maven_jar(
    name = "tukaani_xz",
    artifact = "org.tukaani:xz:1.6",
    attach_source = False,
    sha1 = "05b6f921f1810bdf90e25471968f741f87168b64",
)

maven_jar(
    name = "junit",
    artifact = "junit:junit:4.11",
    sha1 = "4e031bb61df09069aeb2bffb4019e7a5034a4ee0",
)

maven_jar(
    name = "hamcrest_core",
    artifact = "org.hamcrest:hamcrest-core:1.3",
    sha1 = "42a25dc3219429f0e5d060061f71acb49bf010a0",
)

SL_VERS = "1.7.7"

maven_jar(
    name = "slf4j_api",
    artifact = "org.slf4j:slf4j-api:" + SL_VERS,
    sha1 = "2b8019b6249bb05d81d3a3094e468753e2b21311",
)

maven_jar(
    name = "slf4j_simple",
    artifact = "org.slf4j:slf4j-simple:" + SL_VERS,
    sha1 = "8095d0b9f7e0a9cd79a663c740e0f8fb31d0e2c8",
)

GUICE_VERSION = "4.2.0"

maven_jar(
    name = "guice_library",
    artifact = "com.google.inject:guice:" + GUICE_VERSION,
    sha1 = "25e1f4c1d528a1cffabcca0d432f634f3132f6c8",
)

maven_jar(
    name = "guice_assistedinject",
    artifact = "com.google.inject.extensions:guice-assistedinject:" + GUICE_VERSION,
    sha1 = "e7270305960ad7db56f7e30cb9df6be9ff1cfb45",
)

maven_jar(
    name = "aopalliance",
    artifact = "aopalliance:aopalliance:1.0",
    sha1 = "0235ba8b489512805ac13a8f9ea77a1ca5ebe3e8",
)

maven_jar(
    name = "javax_inject",
    artifact = "javax.inject:javax.inject:1",
    sha1 = "6975da39a7040257bd51d21a231b76c915872d38",
)

JETTY_VERSION = "9.3.18.v20170406"

maven_jar(
    name = "servlet",
    artifact = "org.eclipse.jetty:jetty-servlet:" + JETTY_VERSION,
    sha1 = "534e7fa0e4fb6e08f89eb3f6a8c48b4f81ff5738",
)

maven_jar(
    name = "security",
    artifact = "org.eclipse.jetty:jetty-security:" + JETTY_VERSION,
    sha1 = "16b900e91b04511f42b706c925c8af6023d2c05e",
)

maven_jar(
    name = "server",
    artifact = "org.eclipse.jetty:jetty-server:" + JETTY_VERSION,
    sha1 = "0a32feea88cba2d43951d22b60861c643454bb3f",
)

maven_jar(
    name = "continuation",
    artifact = "org.eclipse.jetty:jetty-continuation:" + JETTY_VERSION,
    sha1 = "3c5d89c8204d4a48a360087f95e4cbd4520b5de0",
)

maven_jar(
    name = "http",
    artifact = "org.eclipse.jetty:jetty-http:" + JETTY_VERSION,
    sha1 = "30ece6d732d276442d513b94d914de6fa1075fae",
)

maven_jar(
    name = "io",
    artifact = "org.eclipse.jetty:jetty-io:" + JETTY_VERSION,
    sha1 = "36cb411ee89be1b527b0c10747aa3153267fc3ec",
)

maven_jar(
    name = "util",
    artifact = "org.eclipse.jetty:jetty-util:" + JETTY_VERSION,
    sha1 = "8600b7d028a38cb462eff338de91390b3ff5040e",
)
