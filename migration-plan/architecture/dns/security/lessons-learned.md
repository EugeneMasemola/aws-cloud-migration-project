# Lessons Learned

## Planning Matters

Website migrations require careful planning before any technical changes are made. Backups, DNS access, rollback steps, and testing procedures should be prepared before migration begins.

## DNS Changes Need Care

DNS propagation can take time, so cutover planning is important. Lowering TTL before migration can help reduce downtime and make rollback easier.

## Backups Are Critical

A reliable backup should exist before migration starts. This helps reduce risk if the new environment has issues.

## Documentation Helps Handover

Documenting migration steps, issues, and final configuration makes the project easier to support after completion.

## Security Must Be Maintained

Credentials, client data, and internal system details should never be exposed in public repositories.
