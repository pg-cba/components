## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BaseHarnessFilters } from '@angular/cdk/testing';
import { ComponentHarness } from '@angular/cdk/testing';
import { HarnessPredicate } from '@angular/cdk/testing';
import { ProgressSpinnerMode } from '@angular/material/progress-spinner';

// @public
export class MatProgressSpinnerHarness extends ComponentHarness {
    getMode(): Promise<ProgressSpinnerMode>;
    getValue(): Promise<number | null>;
    static hostSelector: string;
    static with(options?: ProgressSpinnerHarnessFilters): HarnessPredicate<MatProgressSpinnerHarness>;
}

// @public
export interface ProgressSpinnerHarnessFilters extends BaseHarnessFilters {
}

// (No @packageDocumentation comment for this package)

```