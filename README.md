
# Dynatrace Community Dashboards

A community-driven library of ready-to-use Dynatrace assets, organized by technology.

Each technology gets its own folder containing:
- A **dashboard** you can import directly into Dynatrace
- An **OpenPipeline** configuration for processing that technology's data
- A **README** explaining what the assets do and how to use them

## Available technologies

| Technology | Dashboard | OpenPipeline |
|---|---|---|
| [AWS EC2](technologies/aws-ec2) | ✅ | ✅ |
| [Amazon SQS](technologies/amazon-sqs) | ✅ | ✅ |
| [Apache Tomcat](technologies/apache-tomcat) | ✅ | ✅ |

## How it works

1. Browse `technologies/` for the technology you're monitoring.
2. Open its folder and read the `README.md` for setup notes.
3. Import `dashboard.json` into Dynatrace.
4. Import `openpipeline.json` into OpenPipeline.

## Contributing

Want to add a technology or improve an existing one?

1. Copy an existing technology folder as a starting point.
2. Replace the dashboard and OpenPipeline exports with your own.
3. Update the README with a description and setup notes.
4. Open a pull request.

This project is in early, active development — structure and contribution guidelines will evolve as it grows.
