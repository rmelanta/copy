<!--- STARTEXCLUDE --->
# Astra/Spark Migration Tool
*40 minutes, Expert, [Start Building](https://github.com/DataStax-Examples/astra-spark-migration#prerequisites)*

Migrate data from an existing Cassandra cluster to Astra using a Spark application.
<!--- ENDEXCLUDE --->

![image](https://monosnap.com/image/XzDUe9By3ehIJt2ZcQwbSd8Av5sSQY)

## Objectives
* Leverage Spark to migrate data from a Cassandra cluster to Cassandra on AstraDB.

## How this works
We're using Spark to migrate data from a Cassandra cluster to Cassandra on AstraDB.

## Get Started
To build and play with this app, follow the build instructions that are located here: [https://github.com/DataStax-Examples/astra-spark-migration](https://github.com/DataStax-Examples/astra-spark-migration#prerequisites)

<!--- STARTEXCLUDE --->
# Running Astra/Spark Migration Tool
Follow the instructions below to get started.
## Prerequisites
Let's do some initial setup.

### DataStax Astra
1. Create a [DataStax Astra account](https://astra.datastax.com/register?utm_source=github&utm_medium=referral&utm_campaign=astra-spark-migration) if you don't 
already have one:
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-register-basic-auth.png)

2. On the home page. Locate the button **`Add Database`**
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-dashboard.png)

3. Pick **free plan** and a **region** close to you, click configure.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-create-db-1-top.png)
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-create-db-1-bottom.png)

4. Define a **database name**, **keyspace name** and **credentials** (Take note of the DB Password)
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-create-db-2.png)

5. Your Astra DB will be ready when the status will change from *`Pending`* to **`Active`** 💥💥💥 
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-db-active.png)

6. Locate the combo `Organization: <Your email>` on the top navigation. In the drop down menu, click your current organization.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-org-menu-open.png)

7. Scroll down to the bottom of the page and locate `Service Account` in `Security Settings` and select `Copy Credentials` as shown below.
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/astra-org-copy-credentials.png)

### Github
1. Click `Use this template` at the top of the [GitHub Repository](https://github.com/DataStax-Examples/astra-spark-migration):
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-use-template.png)

2. Enter a repository name and click 'Create repository from template':
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-create-repository.png)

3. Clone the repository:
![image](https://raw.githubusercontent.com/DataStax-Examples/sample-app-template/master/screenshots/github-clone.png)
<!--- ENDEXCLUDE --->
