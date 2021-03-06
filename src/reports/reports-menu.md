---
title: Reports Menu
---

Magento provides a wide selection of reports to keep you informed on your marketing efforts, sales products, and customer activity. The Reports menu provides easy access to current information about your sales, products, customers, and promotions.

<!--{% if "Default.CE Only" contains site.edition %}-->
![]({% link images/images/admin-menu-reports.png %}){: .zoom}
_Reports Menu_
<!--{% endif %}-->
<!--{% if "Default.EE-B2B" contains site.edition %}-->
![]({% link images/images-ee/admin-menu-reports-ee.png %}){: .zoom}
_Reports Menu_
<!--{% endif %}-->

## Display the Reports menu

On the _Admin_ sidebar, choose **Reports**.

## Menu Options

### Marketing

A selection of [marketing reports]({% link reports/marketing-reports.md %}), including Products in Cart, Search Terms, Abandoned Carts, and Newsletter Problem Reports.

### Reviews

The selection of product [review reports]({% link reports/review-reports.md %}) includes By Customer and By Product.

### Sales

The selection of [sales reports]({% link reports/sales-reports.md %}) includes Orders, Tax, Invoiced, Shipping, Refunds, Coupons, and settlement reports for PayPal and Braintree.

### Customers

{% if "Default.CE Only" contains site.edition %}The selection of [customer reports]({% link reports/customer-reports.md %}) includes Order Total, Order Account, and New. {% endif %}
{% if "Default.EE-B2B" contains site.edition %}The selection of [customer reports]({% link reports/customer-reports.md %}) includes Order Total, Order Account, New, Wish Lists, and Segments.{% endif %}

### Products

The selection of [product reports]({% link reports/product-reports.md %}) includes Views, Bestsellers, Low Stock, Ordered, and Downloads.

<!--{% if "Default.EE-B2B" contains site.edition %}-->
### Private Sales

The selection of reports for [private sales and events]({% link reports/statistics.md %}) includes Invitation, Invited Customers, and Conversions.

<!--{% endif %}-->
### Statistics

[Statistics]({% link reports/statistics.md %}) is a tool that reduces the performance impact of generating reports by calculating and storing statistical data. Rather than recalculate the statistics every time a report is generated, the stored statistics are used until you refresh the statistics.

### Business Intelligence

Integrated [Business Intelligence]({% link reports/business-intelligence.md %}) tools provide the insight you need to make strategic business decisions.

### Customer Engagement

The [Customer Engagement reporting]({% link reports/customer-engagement.md %}) provides data import and report options for [Engagement Cloud]({% link marketing/dotdigital/engagement-cloud.md %}).
