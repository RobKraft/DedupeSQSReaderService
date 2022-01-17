# DedupeSQSReaderService

This windows service is written in C# .Net 4.8.  It polls an AWS SQS queue every minute (configurable) and launches an executable (configurable) when an SQS message is found.
