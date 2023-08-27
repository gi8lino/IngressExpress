# Kubernetes Ingress Search

This Alfred workflow allows you to search for Kubernetes Ingress resources based on a given prefix and open the corresponding URLs in a web browser.

## Features

Search for Kubernetes Ingress by host prefix.
View the matching Kubernetes Ingress hostnames and their corresponding resource names.
Open selected Ingress URLs in the default web browser.

## Prerequisites

- Alfred 4 with Powerpack
- kubectl installed and configured to talk to your Kubernetes cluster
- jq installed for JSON parsing

## Usage

Trigger the workflow with the Alfred keyword (e.g., i).
Type in the prefix for the Ingress hosts you're interested in (e.g., kubernetes dashboard for hosts like dashboard.example.com).
A list of matching Ingress hosts will be displayed along with their corresponding resource names.
Select an entry to open its URL in your default web browser.

## Notes

This workflow uses the https scheme for all URLs \.
Ensure that the kubectl and jq executables are correctly referenced in the script, especially if they are not installed in standard locations (/usr/local/bin).
