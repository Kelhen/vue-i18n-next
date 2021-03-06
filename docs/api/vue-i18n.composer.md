<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [vue-i18n](./vue-i18n.md) &gt; [Composer](./vue-i18n.composer.md)

## Composer interface

<b>Signature:</b>

```typescript
export interface Composer<Messages = {}, DateTimeFormats = {}, NumberFormats = {}, Message = VueMessageType> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [availableLocales](./vue-i18n.composer.availablelocales.md) | [Locale](./vue-i18n.locale.md)<!-- -->\[\] |  |
|  [datetimeFormats](./vue-i18n.composer.datetimeformats.md) | ComputedRef&lt;DateTimeFormats&gt; |  |
|  [escapeParameter](./vue-i18n.composer.escapeparameter.md) | boolean |  |
|  [fallbackFormat](./vue-i18n.composer.fallbackformat.md) | boolean |  |
|  [fallbackLocale](./vue-i18n.composer.fallbacklocale.md) | WritableComputedRef&lt;[FallbackLocale](./vue-i18n.fallbacklocale.md)<!-- -->&gt; |  |
|  [fallbackRoot](./vue-i18n.composer.fallbackroot.md) | boolean |  |
|  [fallbackWarn](./vue-i18n.composer.fallbackwarn.md) | boolean \| RegExp |  |
|  [id](./vue-i18n.composer.id.md) | number |  |
|  [inheritLocale](./vue-i18n.composer.inheritlocale.md) | boolean |  |
|  [isGlobal](./vue-i18n.composer.isglobal.md) | boolean |  |
|  [locale](./vue-i18n.composer.locale.md) | WritableComputedRef&lt;[Locale](./vue-i18n.locale.md)<!-- -->&gt; |  |
|  [messages](./vue-i18n.composer.messages.md) | ComputedRef&lt;Messages&gt; |  |
|  [missingWarn](./vue-i18n.composer.missingwarn.md) | boolean \| RegExp |  |
|  [modifiers](./vue-i18n.composer.modifiers.md) | [LinkedModifiers](./vue-i18n.linkedmodifiers.md)<!-- -->&lt;Message&gt; |  |
|  [numberFormats](./vue-i18n.composer.numberformats.md) | ComputedRef&lt;NumberFormats&gt; |  |
|  [pluralRules](./vue-i18n.composer.pluralrules.md) | PluralizationRules |  |
|  [warnHtmlMessage](./vue-i18n.composer.warnhtmlmessage.md) | boolean |  |

## Methods

|  Method | Description |
|  --- | --- |
|  [d(value)](./vue-i18n.composer.d.md) |  |
|  [d(value, key)](./vue-i18n.composer.d_1.md) |  |
|  [d(value, key, locale)](./vue-i18n.composer.d_2.md) |  |
|  [d(value, options)](./vue-i18n.composer.d_3.md) |  |
|  [d(args)](./vue-i18n.composer.d_4.md) |  |
|  [getDateTimeFormat(locale)](./vue-i18n.composer.getdatetimeformat.md) |  |
|  [getLocaleMessage(locale)](./vue-i18n.composer.getlocalemessage.md) |  |
|  [getMissingHandler()](./vue-i18n.composer.getmissinghandler.md) |  |
|  [getNumberFormat(locale)](./vue-i18n.composer.getnumberformat.md) |  |
|  [getPostTranslationHandler()](./vue-i18n.composer.getposttranslationhandler.md) |  |
|  [mergeDateTimeFormat(locale, format)](./vue-i18n.composer.mergedatetimeformat.md) |  |
|  [mergeLocaleMessage(locale, message)](./vue-i18n.composer.mergelocalemessage.md) |  |
|  [mergeNumberFormat(locale, format)](./vue-i18n.composer.mergenumberformat.md) |  |
|  [n(value)](./vue-i18n.composer.n.md) |  |
|  [n(value, key)](./vue-i18n.composer.n_1.md) |  |
|  [n(value, key, locale)](./vue-i18n.composer.n_2.md) |  |
|  [n(value, options)](./vue-i18n.composer.n_3.md) |  |
|  [n(args)](./vue-i18n.composer.n_4.md) |  |
|  [setDateTimeFormat(locale, format)](./vue-i18n.composer.setdatetimeformat.md) |  |
|  [setLocaleMessage(locale, message)](./vue-i18n.composer.setlocalemessage.md) |  |
|  [setMissingHandler(handler)](./vue-i18n.composer.setmissinghandler.md) |  |
|  [setNumberFormat(locale, format)](./vue-i18n.composer.setnumberformat.md) |  |
|  [setPostTranslationHandler(handler)](./vue-i18n.composer.setposttranslationhandler.md) |  |
|  [t(key)](./vue-i18n.composer.t.md) |  |
|  [t(key, named)](./vue-i18n.composer.t_9.md) |  |
|  [t(key, named, plural)](./vue-i18n.composer.t_10.md) |  |
|  [t(key, named, defaultMsg)](./vue-i18n.composer.t_11.md) |  |
|  [t(key, named, options)](./vue-i18n.composer.t_12.md) |  |
|  [t(args)](./vue-i18n.composer.t_13.md) |  |
|  [t(key, plural)](./vue-i18n.composer.t_1.md) |  |
|  [t(key, plural, options)](./vue-i18n.composer.t_2.md) |  |
|  [t(key, defaultMsg)](./vue-i18n.composer.t_3.md) |  |
|  [t(key, defaultMsg, options)](./vue-i18n.composer.t_4.md) |  |
|  [t(key, list)](./vue-i18n.composer.t_5.md) |  |
|  [t(key, list, plural)](./vue-i18n.composer.t_6.md) |  |
|  [t(key, list, defaultMsg)](./vue-i18n.composer.t_7.md) |  |
|  [t(key, list, options)](./vue-i18n.composer.t_8.md) |  |
|  [tm(key)](./vue-i18n.composer.tm.md) |  |

