# Pala Interactive information:

## installation command:

```bash
npm install --save github:palainteractive/capacitor-advertising-id#feat/v4
npx cap sync
```

# *** Below is the original @capacitor-community README.md ***


# @capacitor-community/advertising-id

Allows access to the IDFA (iOS) and GAID (Android)

## Install

```bash
npm install @capacitor-community/advertising-id
npx cap sync
```

## API

<docgen-index>

* [`requestTracking()`](#requesttracking)
* [`getAdvertisingId()`](#getadvertisingid)
* [`getAdvertisingStatus()`](#getadvertisingstatus)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### requestTracking()

```typescript
requestTracking() => Promise<{ value: string; }>
```

**Returns:** <code>Promise&lt;{ value: string; }&gt;</code>

--------------------


### getAdvertisingId()

```typescript
getAdvertisingId() => Promise<{ id: string; status: string; }>
```

**Returns:** <code>Promise&lt;{ id: string; status: string; }&gt;</code>

--------------------


### getAdvertisingStatus()

```typescript
getAdvertisingStatus() => Promise<{ status: string; }>
```

**Returns:** <code>Promise&lt;{ status: string; }&gt;</code>

--------------------

</docgen-api>
