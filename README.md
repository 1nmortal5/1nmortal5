
element.style {
    --ytd-video-preview-translate-left: 0px;
    --ytd-video-preview-translate-top: -0.08987060546877501px;
    --ytd-video-preview-original-top-position: 419.0086251831055px;
    --ytd-video-preview-original-horizontal-position: 251.8562469482422px;
    --ytd-video-preview-initial-scale: scale(0.9992812347412109);
    --ytd-video-preview-width: 400px;
    --ytd-video-preview-height: 225px;
}
[hidden] {
    display: none !important;
}
ytd-video-preview {
    --ytd-video-preview-width: 440px;
    --ytd-video-preview-height: 248px;
    --ytd-video-preview-original-top-position: 0;
    --ytd-video-preview-original-horizontal-position: 0;
    --ytd-video-preview-initial-scale: scale(1);
    opacity: 0;
    pointer-events: none;
    position: absolute;
    padding: 12px;
    z-index: 1;
    top: var(--ytd-video-preview-original-top-position);
    left: var(--ytd-video-preview-original-horizontal-position);
    transform: var(--ytd-video-preview-initial-scale) translate(0, 0);
    transform-origin: top;
    will-change: opacity, transform;
    background-color: transparent;
    display: flexbox;
    display: flex;
}
ytd-video-preview[Attributes Style] {
    display: none;
}
ytd-app {
    --app-drawer-width: 240px;
    --ytd-persistent-guide-width: 240px;
    --ytd-permission-role-bottom-bar-height: 30px;
    --ytd-mini-guide-width: 72px;
    --app-drawer-content-container-background-color: var(--yt-spec-base-background);
    background: var(--yt-spec-base-background);
    display: block;
    left: 0;
    min-height: 100%;
    position: absolute;
    right: 0;
    top: 0;
    scrollbar-color: var(--yt-spec-text-secondary) transparent;
}
style attribute {
    font-size: 10px;
    font-family: Roboto, Arial, sans-serif;
}
html[refresh]:not(.style-scope) {
    --paper-input-container-invalid-color: var(--yt-spec-error-indicator);
}
<style>
html:not(.style-scope) {
    --primary-text-color: var(--light-theme-text-color);
    --primary-background-color: var(--light-theme-background-color);
    --secondary-text-color: var(--light-theme-secondary-color);
    --disabled-text-color: var(--light-theme-disabled-color);
    --divider-color: var(--light-theme-divider-color);
    --error-color: #dd2c00;
    --primary-color: #3f51b5;
    --light-primary-color: #c5cae9;
    --dark-primary-color: #303f9f;
    --accent-color: #ff4081;
    --light-accent-color: #ff80ab;
    --dark-accent-color: #f50057;
    --light-theme-background-color: #fff;
    --light-theme-base-color: #000;
    --light-theme-text-color: #212121;
    --light-theme-secondary-color: #737373;
    --light-theme-disabled-color: #9b9b9b;
    --light-theme-divider-color: #dbdbdb;
    --dark-theme-background-color: #212121;
    --dark-theme-base-color: #fff;
    --dark-theme-text-color: #fff;
    --dark-theme-secondary-color: #bcbcbc;
    --dark-theme-disabled-color: #646464;
    --dark-theme-divider-color: #3c3c3c;
    --text-primary-color: var(--dark-theme-text-color);
    --default-primary-color: var(--primary-color);
}
html[refresh], [refresh] {
    --yt-spec-static-brand-red: #f03;
    --yt-spec-static-overlay-background-brand: rgba(225, 0, 45, 0.9);
    --yt-spec-static-brand-black: #000;
}
html[refresh], [refresh] [light] {
    --yt-spec-wordmark-text: #000;
    --yt-spec-error-indicator: #c30027;
}
html[darker-dark-theme-deprecate], [darker-dark-theme-deprecate] {
    --yt-spec-brand-background-solid: var(--yt-spec-raised-background);
    --yt-spec-brand-background-primary: var(--yt-spec-raised-background);
    --yt-spec-brand-background-secondary: var(--yt-spec-raised-background);
    --yt-spec-general-background-a: var(--yt-spec-base-background);
    --yt-spec-general-background-b: var(--yt-spec-base-background);
    --yt-spec-general-background-c: var(--yt-spec-base-background);
    --yt-spec-error-background: var(--yt-spec-inverted-background);
    --yt-spec-badge-chip-background: var(--yt-spec-additive-background);
    --yt-spec-verified-badge-background: var(--yt-spec-additive-background);
    --yt-spec-10-percent-layer: var(--yt-spec-outline);
    --yt-spec-snackbar-background: var(--yt-spec-inverted-background);
}
html[darker-dark-theme], [darker-dark-theme] [light] {
    --yt-spec-text-primary: #0f0f0f;
    --yt-spec-text-primary-inverse: #fff;
}
html[system-icons] {
    --yt-spec-icon-active-other: #030303;
    --yt-spec-icon-inactive: #030303;
    --yt-spec-icon-disabled: #909090;
    --yt-spec-brand-icon-active: #030303;
    --yt-spec-brand-icon-inactive: #030303;
    --yt-button-icon-button-text-color: var(--yt-spec-text-primary);
}
html:not(.style-scope) {
    --paper-dialog-background-color: var(--yt-spec-brand-background-solid);
    --paper-listbox-background-color: var(--yt-spec-brand-background-solid);
    --paper-listbox-color: var(--yt-spec-text-primary);
    --paper-spinner-layer-1-color: var(--yt-spec-text-secondary);
    --paper-spinner-layer-2-color: var(--yt-spec-text-secondary);
    --paper-spinner-layer-3-color: var(--yt-spec-text-secondary);
    --paper-spinner-layer-4-color: var(--yt-spec-text-secondary);
    --paper-spinner-color: var(--yt-spec-text-secondary);
    --paper-input-container-focus-color: var(--yt-spec-themed-blue);
    --paper-input-container-input-color: var(--yt-spec-text-primary);
    --paper-input-container-invalid-color: var(--yt-spec-brand-link-text);
    --paper-checkbox-unchecked-color: var(--yt-spec-icon-inactive);
    --paper-checkbox-unchecked-ink-color: var(--yt-spec-icon-inactive);
    --paper-checkbox-checked-color: var(--yt-spec-call-to-action);
    --paper-checkbox-checked-ink-color: var(--yt-spec-call-to-action);
    --paper-checkbox-label-color: var(--yt-spec-text-primary);
    --paper-checkbox-label-spacing: 16px;
    --paper-checkbox-size: 20px;
    --paper-checkbox-checkmark-color: var(--yt-spec-text-primary-inverse);
    --paper-radio-button-unchecked-color: var(--yt-spec-icon-inactive);
    --paper-radio-button-unchecked-ink-color: var(--yt-spec-icon-inactive);
    --paper-radio-button-checked-color: var(--yt-spec-call-to-action);
    --paper-radio-button-checked-ink-color: var(--yt-spec-call-to-action);
    --paper-radio-button-label-spacing: 16px;
    --paper-radio-button-label-color: var(--yt-spec-text-primary);
    --paper-radio-button-size: 20px;
    --paper-toggle-button-unchecked-bar-color: var(--yt-spec-icon-disabled);
    --paper-toggle-button-unchecked-button-color: var(--yt-spec-icon-inactive);
    --paper-toggle-button-checked-bar-color: var(--yt-spec-icon-disabled);
    --paper-toggle-button-checked-button-color: var(--yt-spec-call-to-action);
    --paper-toggle-button-checked-ink-color: var(--yt-spec-call-to-action);
    --paper-toggle-button-unchecked-ink-color: var(--yt-spec-touch-response);
    --paper-menu-disabled-color: var(--yt-spec-text-primary);
    --paper-menu-background-color: var(--yt-spec-brand-background-solid);
    --paper-menu-color: var(--yt-spec-text-primary);
    --yt-icon-width: 40px;
    --yt-icon-height: 40px;
}
html[typography] {
    --yt-channel-line-height: 3.2rem;
    --yt-navbar-title-line-height: 2.6rem;
    --yt-subheadline-line-height: 2.2rem;
    --yt-link-line-height: 2rem;
    --yt-thumbnail-attribution-font-size: 1.2rem;
    --yt-thumbnail-attribution-line-height: 1.8rem;
    --yt-user-comment-line-height: 2rem;
    --yt-guide-highlight-line-height: 2rem;
    --yt-caption-font-size: 1.2rem;
    --yt-caption-line-height: 1.8rem;
}
html[typography-spacing] {
    --yt-subheadline-letter-spacing: 0.1px;
    --yt-subheadline-link-letter-spacing: 0.15px;
    --yt-link-letter-spacing: 0.25px;
    --yt-thumbnail-attribution-letter-spacing: 0.3px;
    --yt-user-comment-letter-spacing: 0.2px;
    --yt-guide-highlight-letter-spacing: 0.25px;
    --yt-caption-letter-spacing: 0.35px;
    --yt-badge-letter-spacing: 0.35px;
    --yt-tab-system-letter-spacing: 0.5px;
}
html[system-icons] {
    --ytd-searchbox-legacy-button-icon-color: #030303;
}
:root {
    --yt-attributed-string-link-hover-color: unset;
}
html {
    background-color: #fff !important;
    -webkit-text-size-adjust: none;
}
html {
    --ytd-rich-grid-items-per-row: 4;
    --ytd-rich-grid-posts-per-row: 3;
    --ytd-rich-grid-slim-items-per-row: 6;
    --ytd-rich-grid-game-cards-per-row: 6;
    --ytd-rich-grid-mini-game-cards-per-row: 6;
    --ytd-rich-grid-item-margin: 16px;
    --ytd-rich-grid-compact-item-margin: 4px;
    --ytd-rich-grid-shorts-item-margin: 4px;
    --ytd-rich-grid-row-margin: 40px;
    --ytd-rich-grid-gutter-margin: 16px;
    --ytd-rich-grid-item-min-width: 310px;
    --ytd-rich-grid-item-max-width: 500px;
    --ytd-rich-grid-mini-item-min-width: 240px;
    --ytd-rich-grid-mini-item-max-width: 320px;
    --ytd-rich-grid-slim-item-max-width: 220px;
}
html {
    --yt-subscription-product-grid-margin: 24px;
    --yt-subscription-product-grid-margin-two-thirds: 16px;
    --yt-subscription-product-grid-margin-half: 12px;
    --yt-subscription-product-grid-margin-one-third: 8px;
}
html {
    --yt-deprecated-blue-light: hsl(205.9, 80%, 43.1%);
    --yt-deprecated-opalescence-grey-opacity-lighten-3: hsla(0, 0%, 53.3%, 0.4);
    --yt-deprecated-opalescence-soft-grey-opacity-lighten-3: hsla(0, 0%, 93.3%, 0.4);
    --yt-deprecated-luna-black-opacity-lighten-2: hsla(0, 0%, 6.7%, 0.6);
    --yt-deprecated-luna-black-opacity-lighten-3: hsla(0, 0%, 6.7%, 0.4);
    --yt-deprecated-luna-black-opacity-lighten-4: hsla(0, 0%, 6.7%, 0.2);
    --yt-opalescence-dark-grey: hsl(0, 0%, 20%);
    --yt-deprecated-luna-black: hsl(0, 0%, 6.7%);
    --yt-deprecated-white-opacity-lighten-4: hsla(0, 0%, 100%, 0.2);
    --yt-deprecated-opalescence-soft-grey-opacity-lighten-1: hsla(0, 0%, 93.3%, 0.8);
    --yt-deprecated-opalescence-soft-grey: hsl(0, 0%, 93.3%);
    --yt-live-chat-background-color: var(--yt-spec-base-background);
    --yt-live-chat-secondary-background-color: var(--yt-deprecated-opalescence-soft-grey);
    --yt-live-chat-action-panel-background-color: var(--yt-spec-base-background);
    --yt-live-chat-action-panel-background-color-transparent: hsla(0, 0%, 97%, 0.8);
    --yt-live-chat-additive-background-inverse: var(--yt-spec-white-1-alpha-10);
    --yt-live-chat-mode-change-background-color: var(--yt-deprecated-opalescence-soft-grey-opacity-lighten-3);
    --yt-live-chat-primary-text-color: var(--yt-spec-text-primary);
    --yt-live-chat-secondary-text-color: var(--yt-deprecated-luna-black-opacity-lighten-2);
    --yt-live-chat-secondary-text-color-inverse: var(--yt-spec-grey-2);
    --yt-live-chat-tertiary-text-color: var(--yt-deprecated-luna-black-opacity-lighten-3);
    --yt-live-chat-tertiary-text-color-inverse: var(--yt-spec-white-1-alpha-30);
    --yt-live-chat-text-input-field-inactive-underline-color: #b8b8b8;
    --yt-live-chat-text-input-field-placeholder-color: var(--yt-deprecated-luna-black-opacity-lighten-2);
    --yt-live-chat-text-input-field-underline-transition-duration: 0.25s;
    --yt-live-chat-icon-button-color: var(--yt-live-chat-primary-text-color);
    --yt-live-chat-enabled-send-button-color: #4285f4;
    --yt-live-chat-disabled-icon-button-color: var(--yt-deprecated-luna-black-opacity-lighten-4);
    --yt-live-chat-picker-button-color: var(--yt-deprecated-luna-black-opacity-lighten-3);
    --yt-live-chat-picker-button-active-color: var(--yt-deprecated-luna-black-opacity-lighten-1);
    --yt-live-chat-picker-button-disabled-color: var(--yt-live-chat-disabled-icon-button-color);
    --yt-live-chat-picker-button-hover-color: var(--yt-deprecated-luna-black-opacity-lighten-2);
    --yt-live-chat-mention-background-color: #ff5722;
    --yt-live-chat-mention-text-color: var(--yt-spec-static-overlay-text-primary);
    --yt-live-chat-deleted-message-color: rgba(0, 0, 0, 0.5);
    --yt-live-chat-deleted-message-bar-color: rgba(11, 11, 11, 0.2);
    --yt-live-chat-disabled-button-background-color: var(--yt-deprecated-opalescence-soft-grey);
    --yt-live-chat-disabled-button-text-color: var(--yt-deprecated-luna-black-opacity-lighten-3);
    --yt-live-chat-sub-panel-background-color: var(--yt-spec-base-background);
    --yt-live-chat-sub-panel-background-color-transparent: var(--yt-spec-base-background);
    --yt-live-chat-header-background-color: var(--yt-spec-base-background);
    --yt-live-chat-header-button-color: var(--yt-deprecated-luna-black);
    --yt-live-chat-header-bottom-border: 1px solid var(--yt-spec-10-percent-layer);
    --yt-live-chat-count-color-early-warning: hsl(40, 76%, 55%);
    --yt-live-chat-count-color-error: hsl(10, 51%, 49%);
    --yt-live-chat-error-message-color: hsl(10, 51%, 49%);
    --yt-live-chat-reconnect-message-color: hsla(0, 0%, 7%, 0.2);
    --yt-live-chat-moderator-color: hsl(225, 84%, 66%);
    --yt-live-chat-new-moderator-color: var(--yt-spec-call-to-action);
    --yt-live-chat-owner-color: hsl(40, 76%, 55%);
Show all properties (95 more)
}
html {
    --yt-deprecated-luna-black: hsl(0, 0%, 6.7%);
    --yt-deprecated-opalescence-grey: hsl(0, 0%, 53.3%);
    --yt-deprecated-opalescence-soft-grey: hsl(0, 0%, 93.3%);
    --yt-deprecated-blue: hsl(206.1, 79.3%, 52.7%);
    --yt-deprecated-luna-black-opacity-lighten-1: hsla(0, 0%, 6.7%, 0.8);
    --yt-deprecated-luna-black-opacity-lighten-2: hsla(0, 0%, 6.7%, 0.6);
    --yt-deprecated-luna-black-opacity-lighten-3: hsla(0, 0%, 6.7%, 0.4);
    --yt-deprecated-opalescence-soft-grey-opacity-lighten-3: hsla(0, 0%, 93.3%, 0.4);
    --yt-deprecated-white-opacity-lighten-1: hsla(0, 0%, 100%, 0.8);
    --yt-deprecated-white-opacity-lighten-2: hsla(0, 0%, 100%, 0.6);
    --yt-deprecated-dark-surface-100: hsl(0, 0%, 7%);
}
html {
    --yt-spec-white-1: #fff;
    --yt-spec-white-2: #f9f9f9;
    --yt-spec-white-3: #f1f1f1;
    --yt-spec-white-4: #e9e9e9;
    --yt-spec-black-1: #282828;
    --yt-spec-black-2: #1f1f1f;
    --yt-spec-black-3: #161616;
    --yt-spec-black-4: #0d0d0d;
    --yt-spec-black-pure: #000;
    --yt-spec-grey-1: #ccc;
    --yt-spec-grey-2: #aaa;
    --yt-spec-grey-3: #909090;
    --yt-spec-grey-4: #717171;
    --yt-spec-grey-5: #606060;
    --yt-brand-youtube-red: #f00;
    --yt-brand-medium-red: #c00;
    --yt-brand-light-red: #ff4e45;
    --yt-spec-red-30: #ff8983;
    --yt-spec-red-70: #990412;
    --yt-spec-pale-blue: #f2f8ff;
    --yt-spec-light-blue: #3ea6ff;
    --yt-spec-dark-blue: #065fd4;
    --yt-spec-navy-blue: #252a3a;
    --yt-spec-light-green: #2ba640;
    --yt-spec-dark-green: #107516;
    --yt-spec-yellow: #fbc02d;
    --yt-spec-black-pure-alpha-5: rgba(0, 0, 0, 0.05);
    --yt-spec-black-pure-alpha-10: rgba(0, 0, 0, 0.1);
    --yt-spec-black-pure-alpha-15: rgba(0, 0, 0, 0.15);
    --yt-spec-black-pure-alpha-30: rgba(0, 0, 0, 0.3);
    --yt-spec-black-pure-alpha-60: rgba(0, 0, 0, 0.6);
    --yt-spec-black-pure-alpha-80: rgba(0, 0, 0, 0.8);
    --yt-spec-black-1-alpha-98: rgba(40, 40, 40, 0.98);
    --yt-spec-black-1-alpha-95: rgba(40, 40, 40, 0.95);
    --yt-spec-white-1-alpha-10: rgba(255, 255, 255, 0.1);
    --yt-spec-white-1-alpha-20: rgba(255, 255, 255, 0.2);
    --yt-spec-white-1-alpha-25: rgba(255, 255, 255, 0.25);
    --yt-spec-white-1-alpha-30: rgba(255, 255, 255, 0.3);
    --yt-spec-white-1-alpha-70: rgba(255, 255, 255, 0.7);
    --yt-spec-white-1-alpha-95: rgba(255, 255, 255, 0.95);
    --yt-spec-white-1-alpha-98: rgba(255, 255, 255, 0.98);
    --yt-brand-medium-red-alpha-90: rgba(204, 0, 0, 0.9);
    --yt-brand-medium-red-alpha-30: rgba(204, 0, 0, 0.3);
    --yt-brand-light-red-alpha-30: rgba(255, 78, 69, 0.3);
    --yt-spec-light-blue-alpha-30: rgba(62, 166, 255, 0.3);
    --yt-spec-dark-blue-alpha-30: rgba(6, 95, 212, 0.3);
}
html, [light] {
    --yt-spec-base-background: #fff;
    --yt-spec-raised-background: #fff;
    --yt-spec-menu-background: #fff;
    --yt-spec-inverted-background: #0f0f0f;
    --yt-spec-additive-background: rgba(0, 0, 0, 0.05);
    --yt-spec-outline: rgba(0, 0, 0, 0.1);
    --yt-spec-outline-inverse: rgba(255, 255, 255, 0.2);
    --yt-spec-outline-inverse-medium: rgba(255, 255, 255, 0.3);
    --yt-spec-shadow: rgba(0, 0, 0, 0.25);
    --yt-spec-text-primary: #030303;
    --yt-spec-text-primary-inverse: #fff;
    --yt-spec-text-secondary: #606060;
    --yt-spec-text-disabled: #909090;
    --yt-spec-call-to-action: #065fd4;
    --yt-spec-call-to-action-inverse: #3ea6ff;
    --yt-spec-suggested-action: #def1ff;
    --yt-spec-suggested-action-inverse: #263850;
    --yt-spec-icon-active-other: #606060;
    --yt-spec-icon-inactive: #909090;
    --yt-spec-icon-disabled: #ccc;
    --yt-spec-button-chip-background-hover: rgba(0, 0, 0, 0.1);
    --yt-spec-touch-response: #000;
    --yt-spec-touch-response-inverse: #fff;
    --yt-spec-brand-icon-active: #f00;
    --yt-spec-brand-icon-inactive: #606060;
    --yt-spec-red-indicator: #e1002d;
    --yt-spec-wordmark-text: #212121;
    --yt-spec-error-indicator: #990412;
    --yt-spec-error-background-red: rgba(255, 85, 119, 0.2);
    --yt-spec-themed-blue: #065fd4;
    --yt-spec-themed-green: #107516;
    --yt-spec-ad-indicator: #00716c;
    --yt-spec-themed-overlay-background: rgba(255, 255, 255, 0.7);
    --yt-spec-commerce-badge-background: #deffde;
    --yt-spec-static-white-background: #fff;
    --yt-spec-static-black: #0f0f0f;
    --yt-spec-static-brand-red: #f00;
    --yt-spec-static-brand-white: #fff;
    --yt-spec-static-brand-black: #212121;
    --yt-spec-static-clear-color: rgba(255, 255, 255, 0);
    --yt-spec-static-clear-black: rgba(0, 0, 0, 0);
    --yt-spec-static-ad-yellow: #fbc02d;
    --yt-spec-static-grey: #606060;
    --yt-spec-brand-red-contrast: #c30027;
    --yt-spec-static-overlay-additive-background: rgba(40, 40, 40, 0.6);
    --yt-spec-static-overlay-background-solid: #000;
    --yt-spec-static-overlay-background-heavy: rgba(0, 0, 0, 0.8);
    --yt-spec-static-overlay-background-medium: rgba(0, 0, 0, 0.6);
    --yt-spec-static-overlay-background-medium-light: rgba(0, 0, 0, 0.3);
    --yt-spec-static-overlay-background-light: rgba(0, 0, 0, 0.1);
Show all properties (66 more)
}
html {
    --yt-navbar-title-font-size: 1.8rem;
    --ytd-navbar-title-font-size: var(--yt-navbar-title-font-size);
    --ytd-navbar-title-font-weight: 400;
    --ytd-navbar-title-line-height: var(--yt-navbar-title-line-height, 2.4rem);
    --ytd-subheadline-font-size: var(--yt-subheadline-font-size, 1.6rem);
    --ytd-subheadline-font-weight: 400;
    --ytd-subheadline-line-height: var(--yt-subheadline-line-height, 2rem);
    --ytd-subheadline-letter-spacing: var(--yt-subheadline-letter-spacing, normal);
    --ytd-link-font-size: var(--yt-link-font-size, 1.4rem);
    --ytd-link-font-weight: 500;
    --ytd-link-line-height: var(--yt-link-line-height, 1.6rem);
    --ytd-link-letter-spacing: var(--yt-link-letter-spacing, normal);
    --ytd-user-comment-font-size: var(--yt-user-comment-font-size, 1.4rem);
    --ytd-user-comment-font-weight: 400;
    --ytd-user-comment-line-height: var(--yt-user-comment-line-height, 2.1rem);
    --ytd-user-comment-letter-spacing: var(--yt-user-comment-letter-spacing, normal);
    --ytd-tab-system-font-size: var(--yt-tab-system-font-size, 1.4rem);
    --ytd-tab-system-font-weight: 500;
    --ytd-tab-system-letter-spacing: var(--yt-tab-system-letter-spacing, 0.007px);
    --ytd-tab-system-text-transform: uppercase;
    --ytd-caption-font-size: var(--yt-caption-font-size, 1.3rem);
    --ytd-caption-line-height: var(--yt-caption-line-height, normal);
    --ytd-caption-font-weight: 500;
    --ytd-caption-letter-spacing: var(--yt-caption-letter-spacing, 0.007px);
    --ytd-caption-text-transform: uppercase;
    --ytd-mini-attribution-font-size: 1.2rem;
    --ytd-mini-attribution-font-weight: 400;
    --ytd-mini-attribution-line-height: 1.5rem;
    --ytd-code-snippet-font-size: 1.4rem;
    --ytd-code-snippet-line-height: 2.4rem;
}
html {
    --ytd-rich-grid-items-per-row: 4;
    --ytd-rich-grid-posts-per-row: 3;
    --ytd-rich-grid-slim-items-per-row: 6;
    --ytd-rich-grid-game-cards-per-row: 6;
    --ytd-rich-grid-mini-game-cards-per-row: 6;
    --ytd-rich-grid-item-margin: 16px;
    --ytd-rich-grid-compact-item-margin: 4px;
    --ytd-rich-grid-shorts-item-margin: 4px;
    --ytd-rich-grid-row-margin: 40px;
    --ytd-rich-grid-gutter-margin: 16px;
    --ytd-rich-grid-item-min-width: 310px;
    --ytd-rich-grid-item-max-width: 500px;
    --ytd-rich-grid-mini-item-min-width: 240px;
    --ytd-rich-grid-mini-item-max-width: 320px;
    --ytd-rich-grid-slim-item-max-width: 220px;
}
html {
    --ytd-grid-base: 103px;
    --ytd-margin-base: 4px;
    --ytd-avatar-size: 32px;
    --ytd-toolbar-height: 56px;
    --ytd-margin-2x: 8px;
    --ytd-margin-3x: 12px;
    --ytd-margin-4x: 16px;
    --ytd-margin-5x: 20px;
    --ytd-margin-6x: 24px;
    --ytd-margin-7x: 28px;
    --ytd-margin-8x: 32px;
    --ytd-margin-9x: 36px;
    --ytd-margin-10x: 40px;
    --ytd-margin-11x: 44px;
    --ytd-margin-12x: 48px;
    --ytd-margin-14x: 56px;
    --ytd-margin-16x: 64px;
    --ytd-margin-17x: 68px;
    --ytd-margin-24x: 96px;
    --ytd-margin-25x: 100px;
    --ytd-margin-35x: 140px;
    --ytd-neg-margin-base: -4px;
    --ytd-neg-margin-2x: -8px;
    --ytd-neg-margin-3x: -12px;
    --ytd-neg-margin-4x: -16px;
    --ytd-neg-margin-5x: -20px;
    --ytd-neg-margin-6x: -24px;
    --ytd-neg-margin-7x: -28px;
    --ytd-neg-margin-8x: -32px;
    --ytd-neg-margin-10x: -40px;
    --ytd-neg-margin-11x: -44px;
    --ytd-neg-margin-12x: -48px;
    --ytd-neg-margin-14x: -56px;
    --ytd-neg-margin-16x: -64px;
    --ytd-neg-margin-24x: -96px;
    --ytd-neg-margin-25x: -100px;
    --yt-report-form-modal-renderer-min-width: 250px;
    --yt-legal-report-details-form-renderer-min-width: 250px;
    --yt-upsell-dialog-layout-vertical-width: 400px;
    --yt-upsell-dialog-layout-horizontal-width: 800px;
}
html {
    --yt-button-margin: 0;
    --yt-button-padding: 10px 16px;
    --yt-button-padding-minus-border: 9px 15px;
    --yt-button-padding-minus-focus-outline: 8px 14px;
    --yt-button-padding-minus-focus-outline-width: 2px;
    --yt-button-with-icon-padding-minus-focus-outline: 4px 14px;
    --yt-button-border-radius: 2px;
}
html {
    --paper-tooltip-delay-in: 1ms;
    --paper-tooltip-delay-out: 0;
    --paper-tooltip-duration-in: 150ms;
    --paper-tooltip-duration-out: 75ms;
    --yt-button-tooltip-z-index: 2300;
    --iron-overlay-backdrop-opacity: 0.3;
    --paper-tab-content-focused-font-weight: 500;
    --paper-dialog-background-color: var(--yt-spec-raised-background);
    --paper-listbox-background-color: var(--yt-spec-menu-background);
    --paper-menu-background-color: var(--yt-spec-menu-background);
}
html {
    scrollbar-color: var(--yt-spec-text-secondary) transparent;
}
html {
    --ytd-z-index-report-form-overlay: 100;
    --ytd-z-index-engagement-panel-scrim: 600;
    --ytd-z-index-engagement-panel-scrimmed: 601;
    --ytd-z-index-toggle-button-tooltip: 2300;
    --ytd-z-index-miniplayer-bar: 2008;
    --ytd-z-index-masthead: 2020;
    --ytd-z-index-user-mention-suggestions-container: 2022;
    --ytd-z-index-notification: 2024;
    --ytd-z-index-miniplayer: 2016;
    --ytd-z-index-channel-name: 300;
    --ytd-thumbnail-height: 118px;
    --ytd-grid-1-columns-width: 214px;
    --ytd-grid-2-columns-width: 428px;
    --ytd-grid-3-columns-width: 642px;
    --ytd-grid-4-columns-width: 856px;
    --ytd-grid-5-columns-width: 1070px;
    --ytd-grid-6-columns-width: 1284px;
    --ytd-grid-max-width: 1284px;
    --ytd-scrollbar-width: 8px;
    --ytd-default-promo-panel-renderer-height: 600px;
}
html {
    --ytd-searchbox-border-color: hsla(0, 0%, 53.3%, 0.2);
    --ytd-searchbox-legacy-border-color: #ccc;
    --ytd-searchbox-legacy-border-shadow-color: #eee;
    --ytd-searchbox-legacy-button-color: #f8f8f8;
    --ytd-searchbox-legacy-button-border-color: #d3d3d3;
    --ytd-searchbox-legacy-button-focus-color: #e9e9e9;
    --ytd-searchbox-legacy-button-hover-color: #f0f0f0;
    --ytd-searchbox-legacy-button-hover-border-color: #c6c6c6;
    --ytd-searchbox-legacy-button-icon-color: #333;
    --ytd-searchbox-background: hsl(0, 0%, 100%);
    --ytd-searchbox-text-color: hsl(0, 0%, 6.7%);
}
