# # Offer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**allowCounterOffer** | **bool** | If set to &lt;code&gt;true&lt;/code&gt;, the buyer is allowed to make a counter-offer to the seller&#39;s offer. | [optional]
**buyer** | [**\macropage\SDKs\ebay\rest\negotiation\Model\User**](User.md) |  | [optional]
**creationDate** | **string** | The date and time when the seller&#39;s offer was created.  &lt;br&gt;&lt;br&gt;The returned timestamp is formatted as an &lt;a href&#x3D;\&quot;https://www.iso.org/iso-8601-date-and-time-format.html\&quot; title&#x3D;\&quot;https://www.iso.org\&quot; target&#x3D;\&quot;_blank\&quot;&gt;ISO 8601&lt;/a&gt; string, which is based on the 24-hour Coordinated Universal Time (UTC) clock.  &lt;br&gt;&lt;br&gt;&lt;b&gt;Format:&lt;/b&gt; &lt;code&gt;[YYYY]-[MM]-[DD]T[hh]:[mm]:[ss].[sss]Z&lt;/code&gt; &lt;br&gt;&lt;b&gt;Example:&lt;/b&gt; &lt;code&gt;2018-08-20T07:09:00.000Z&lt;/code&gt; | [optional]
**initiatedBy** | **string** | The eBay &lt;b&gt;UserName&lt;/b&gt; of the user (seller) who initiated the offer. | [optional]
**lastModifiedDate** | **string** | The date and time when the offer was last modified.  &lt;br&gt;&lt;br&gt;The returned timestamp is formatted as an &lt;a href&#x3D;\&quot;http://www.iso.org/iso/home/standards/iso8601.htm\&quot; target&#x3D;\&quot;_blank\&quot;&gt;ISO 8601&lt;/a&gt; string. | [optional]
**message** | **string** | A seller-defined message related to the offer being made. This message is sent to the list of \&quot;interested\&quot; buyers along with the offer message from eBay. | [optional]
**offerDuration** | [**\macropage\SDKs\ebay\rest\negotiation\Model\TimeDuration**](TimeDuration.md) |  | [optional]
**offeredItems** | [**\macropage\SDKs\ebay\rest\negotiation\Model\OfferedItem[]**](OfferedItem.md) | The list of items associated with the offer. &lt;br&gt;&lt;br&gt;Currently, the offer list is restricted to a single offer. | [optional]
**offerId** | **string** | A unique eBay-assigned identifier for the offer. | [optional]
**offerStatus** | **string** | The current state, or status, of an offer.  &lt;br&gt;&lt;br&gt;Status states include &lt;code&gt;PENDING&lt;/code&gt;, &lt;code&gt;COUNTERED&lt;/code&gt;, &lt;code&gt;ACCEPTED&lt;/code&gt;, and &lt;code&gt;DECLINED&lt;/code&gt;. For implementation help, refer to &lt;a href&#x3D;&#39;https://developer.ebay.com/api-docs/sell/negotiation/types/api:OfferStatusEnum&#39;&gt;eBay API documentation&lt;/a&gt; | [optional]
**offerType** | **string** | The type of offer being made. For implementation help, refer to &lt;a href&#x3D;&#39;https://developer.ebay.com/api-docs/sell/negotiation/types/api:OfferTypeEnum&#39;&gt;eBay API documentation&lt;/a&gt; | [optional]
**revision** | **string** | A unique, eBay-assigned ID for the revision of the offer. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
