<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Interface Material Design</title>

    <style>
      body {
        display: flex;
        align-items: center;
        flex-direction: column;
        font-family: "Roboto", sans-serif;
        background-color: #f5f5f5;
        margin: 0;
        padding: 20px;
      }
      
      :root {
        --lv-font-weight-extra-light: 200;
        --mat-button-outlined-label-text-size: 1rem;
        --mat-form-field-filled-with-label-container-padding-bottom: 8px;
        --lv-sizing-6xl: 4.5rem;
        --mat-slide-toggle-disabled-unselected-handle-opacity: .38;
        --lv-color-warn-50: #ffecf1;
        --mat-form-field-outlined-outline-color: rgba(0, 0, 0, .38);
        --mat-dialog-container-shape: 4px;
        --mat-button-tonal-container-height: 36px;
        --mat-button-filled-icon-spacing: 8px;
        --mat-stepper-header-done-state-icon-foreground-color: white;
        --mat-sidenav-container-width: auto;
        --lv-sizing-neg-pct-100: -100%;
        --alpha-dark-8: rgb(0 0 0 / .8);
        --lv-secondary: #323232;
        --mat-dialog-subhead-color: rgba(0, 0, 0, .87);
        --lv-light: #dbdbdb;
        --mat-datepicker-calendar-container-elevation-shadow: 0px 2px 4px -1px rgba(0, 0, 0, .2), 0px 4px 5px 0px rgba(0, 0, 0, .14), 0px 1px 10px 0px rgba(0, 0, 0, .12);
        --ui-sizing-xl: 1.5rem;
        --mat-toolbar-title-text-weight: 500;
        --mat-slide-toggle-selected-handle-color: #ff8114;
        --mat-autocomplete-background-color: white;
        --mat-slider-with-overlap-handle-outline-color: rgba(0, 0, 0, .87);
        --mat-menu-item-label-text-line-height: 1.2rem;
        --mat-select-enabled-trigger-text-color: rgba(0, 0, 0, .87);
        --mat-list-list-item-focus-label-text-color: rgba(0, 0, 0, .87);
        --lv-sizing-pct-90: 90%;
        --mat-button-text-disabled-state-layer-color: rgba(0, 0, 0, .54);
        --mat-slide-toggle-unselected-handle-color: rgba(0, 0, 0, .54);
        --alpha-dark-1: rgb(0 0 0 / .1);
        --mat-button-toggle-label-text-line-height: 1.2rem;
        --mat-slide-toggle-touch-target-display: block;
        --mat-stepper-header-hover-state-layer-color: color-mix(in srgb, rgba(0, 0, 0, .87) 4%, transparent);
        --mat-app-elevation-shadow-level-10: 0px 6px 6px -3px rgba(0, 0, 0, .2), 0px 10px 14px 1px rgba(0, 0, 0, .14), 0px 4px 18px 3px rgba(0, 0, 0, .12);
        --mat-button-protected-hover-container-elevation-shadow: 0px 2px 4px -1px rgba(0, 0, 0, .2), 0px 4px 5px 0px rgba(0, 0, 0, .14), 0px 1px 10px 0px rgba(0, 0, 0, .12);
        --mat-table-footer-supporting-text-tracking: normal;
        --mat-table-row-item-outline-width: 1px;
        --mat-expansion-header-text-color: rgba(0, 0, 0, .87);
        --mat-button-outlined-icon-offset: -4px;
        --lv-avatar-green-bg: #dcfce7;
        --mat-datepicker-calendar-container-touch-shape: 4px;
        --mat-form-field-filled-active-indicator-height: 1px;
        --mat-fab-small-hover-container-elevation-shadow: 0px 5px 5px -3px rgba(0, 0, 0, .2), 0px 8px 10px 1px rgba(0, 0, 0, .14), 0px 3px 14px 2px rgba(0, 0, 0, .12);
        --mat-button-tonal-disabled-state-layer-color: rgba(0, 0, 0, .54);
        --mat-button-filled-container-shape: 4px;
        --lv-font-family: "Roboto", sans-serif;
        --mat-button-outlined-label-text-color: rgba(0, 0, 0, .87);
        --ui-yellow-ad: #EAB308;
        --mat-fab-small-disabled-state-container-color: color-mix(in srgb, rgba(0, 0, 0, .87) 12%, transparent);
        --mat-slider-handle-color: #ff8114;
        --amber-500: #fd9a00;
        --mat-fab-small-touch-target-size: 48px;
        --mat-form-field-enabled-select-arrow-color: rgba(0, 0, 0, .54);
        --mat-stepper-header-height: 72px;
        --ui-sizing-l: 1.25rem;
        --mat-badge-small-size-container-overlap-offset: -8px;
        --mat-slide-toggle-touch-target-size: 48px;
        --lv-red: #dc3545;
        --lv-font-size-900: 2.5rem;
        --mat-badge-large-size-text-size: 24px;
        --lv-border-radius-m: 1rem;
        --mat-form-field-filled-with-label-container-padding-top: 24px;
        --mat-radio-touch-target-display: block;
        --lv-avatar-lime-text: #84cc16;
        --mat-form-field-filled-label-text-tracking: normal;
        --mat-slide-toggle-unselected-handle-horizontal-margin: 0;
        --ui-coral-hover: #E85A5D;
        --lv-extra-spacing-xl: 2.25rem;
        --mat-datepicker-calendar-container-shape: 4px;
        --ui-green-light: #E9F2DD;
        --lv-letter-spacing-small: .02em;
        --mat-dialog-subhead-weight: 500;
        --mat-card-filled-container-elevation: 0px 0px 0px 0px rgba(0, 0, 0, .2), 0px 0px 0px 0px rgba(0, 0, 0, .14), 0px 0px 0px 0px rgba(0, 0, 0, .12);
        --mat-button-outlined-focus-state-layer-opacity: .12;
        --lv-blue-hover: #003e80;
        --lv-color-accent-400: #ababab;
        --mat-button-protected-container-shape: 4px;
        --ui-font-size-900: 2.5rem;
        --ui-sizing-9xl: 6rem;
        --lv-primary: #ff8114;
        --mat-form-field-filled-error-active-indicator-color: #fd464e;
        --mat-menu-item-with-icon-trailing-spacing: 16px;
        --mat-button-filled-label-text-transform: none;
        --mat-fab-extended-container-shape: 24px;
        --mat-form-field-outlined-error-label-text-color: #fd464e;
        --lv-font-weight-light: 300;
        --mat-dialog-content-padding: 20px 24px;
        --mat-sidenav-container-elevation-shadow: 0px 8px 10px -5px rgba(0, 0, 0, .2), 0px 16px 24px 2px rgba(0, 0, 0, .14), 0px 6px 30px 5px rgba(0, 0, 0, .12);
        --ui-spacing-2xs: .25rem;
        --mat-list-list-item-leading-icon-end-space: 32px;
        --alpha-dark-4: rgb(0 0 0 / .4);
        --mat-fab-extended-focus-container-elevation-shadow: 0px 5px 5px -3px rgba(0, 0, 0, .2), 0px 8px 10px 1px rgba(0, 0, 0, .14), 0px 3px 14px 2px rgba(0, 0, 0, .12);
        --mat-icon-button-touch-target-display: block;
        --lv-surface-3: #f5f5f5;
        --mat-paginator-container-background-color: white;
        --mat-pseudo-checkbox-minimal-selected-checkmark-color: #8a8a8a;
        --lv-color-accent-600: #636363;
        --mat-form-field-leading-icon-color: transparent;
        --lv-avatar-violet-text: #8b5cf6;
        --lv-border-radius-full: 50%;
        --mat-slide-toggle-unselected-pressed-handle-color: #424242;
        --ui-spacing-4xl: 3rem;
        --mat-expansion-header-hover-state-layer-color: color-mix(in srgb, rgba(0, 0, 0, .87) 4%, transparent);
        --lv-avatar-red-bg: #fee2e2;
        --mat-expansion-container-text-tracking: normal;
        --lv-extra-sizing-4xl: 12.5rem;
        --mat-table-header-headline-tracking: .0071428571em;
        --mat-badge-large-size-container-padding: 0;
        --mat-checkbox-unselected-pressed-state-layer-color: rgba(0, 0, 0, .87);
        --mat-card-elevated-container-color: white;
        --mat-select-placeholder-text-color: rgba(0, 0, 0, .54);
        --alpha-light-1: rgb(255 255 255 / .1);
        --lv-extra-sizing-3xl: 9.375rem;
        --mat-slide-toggle-disabled-unselected-track-color: rgba(0, 0, 0, .87);
        --mat-form-field-outlined-outline-width: 1px;
        --lv-sizing-pct-60: 60%;
        --mat-checkbox-unselected-hover-icon-color: rgba(0, 0, 0, .87);
        --lv-color-warn-200: #f19ea6;
        --lv-letter-spacing-normal: 0;
        --lv-avatar-pink-text: #ec4899;
        --lv-font-weight-bold: 700;
        --mat-checkbox-disabled-selected-icon-color: color-mix(in srgb, rgba(0, 0, 0, .87) 38%, transparent);
        --mat-button-protected-touch-target-display: block;
        --lv-sizing-pct-50: 50%;
        --mat-form-field-outlined-input-text-placeholder-color: rgba(0, 0, 0, .54);
        --mat-expansion-header-text-line-height: normal;
        --lv-avatar-purple-text: #a855f7;
        --mat-card-title-text-font: Roboto, sans-serif;
        --lv-outline-1: rgb(0 0 0 / .5);
        --mat-button-toggle-text-color: rgba(0, 0, 0, .87);
        --mat-icon-button-touch-target-size: 48px;
        --mat-slide-toggle-unselected-icon-size: 18px;
        --mat-form-field-filled-disabled-input-text-color: color-mix(in srgb, rgba(0, 0, 0, .87) 38%, transparent);
        --ui-orange-hover: #e68900;
        --red-700: #b91c1c;
        --lv-popover-width-sm: 28.125rem;
        --mat-slider-with-overlap-handle-outline-width: 1px;
        --mat-select-trigger-text-font: Roboto, sans-serif;
        --mat-slide-toggle-handle-shape: 10px;
        --mat-list-list-item-hover-label-text-color: rgba(0, 0, 0, .87);
        --mat-button-filled-disabled-container-color: color-mix(in srgb, rgba(0, 0, 0, .87) 12%, transparent);
        --mat-tooltip-container-shape: 4px;
        --mat-button-protected-label-text-tracking: normal;
        --mat-form-field-filled-label-text-font: Roboto, sans-serif;
        --mat-fab-small-foreground-color: rgba(0, 0, 0, .87);
        --mat-checkbox-label-text-size: 1.2rem;
        --tw-space-y-reverse: 0;
        --mat-app-elevation-shadow-level-22: 0px 10px 14px -6px rgba(0, 0, 0, .2), 0px 22px 35px 3px rgba(0, 0, 0, .14), 0px 8px 42px 7px rgba(0, 0, 0, .12);
        --mat-checkbox-unselected-focus-state-layer-color: rgba(0, 0, 0, .87);
        --lv-avatar-red-text: #ef4444;
        --mat-form-field-subscript-text-size: 1rem;
        --mat-icon-color: inherit;
        --mat-button-text-pressed-state-layer-opacity: .12;
        --lv-sizing-l: 1.5rem;
        --ui-font-family-secondary: Inter, sans-serif;
        --mat-button-text-focus-state-layer-opacity: .12;
      }
    </style>
  </head>
  <body>

    <!-- O conteúdo da sua interface vai aqui -->

  </body>
</html>

