# Bisq MailChimp Archive

This is an export of the Bisq MailChimp email archive, created after MailChimp disabled Bisq's account pursuant to their new [acceptable use policy](https://mailchimp.com/legal/acceptable_use/) which reads as follows:

> [W]e cannot allow businesses involved in any aspect of the sale, transaction, exchange, storage, marketing or production of cryptocurrencies, virtual currencies, and any digital assets related to an Initial Coin Offering, to use MailChimp to facilitate or support any of those activities.

See https://github.com/bisq-network/roles/issues/27#issuecomment-386278906 and https://github.com/bisq-network/mailchimp/issues/9 for further details.

The contents of this this repository were created by spidering Bisq's MailChimp email archive with the command below, such that anyone can see and judge the kind of mailing list behavior that Bisq had engaged in prior to having our account disabled.

    wget -e robots=off \
        --span-hosts \
        --recursive \
        --no-clobber \
        --page-requisites \
        --html-extension \
        --convert-links \
        --no-parent \
        --domains us9.campaign-archive.com,eepurl.com \
        'https://us9.campaign-archive.com/home/?u=fee3c64b1504e7835a98b0ed3&id=dc09b9ca64'

The results can be viewed at https://bisq-network.github.io/mailchimp.

We had been paying customers for many months, and never promoted or even mentioned any scamcoins, ICOs or the like. We mailed our subscribers very infrequently, indeed to the point where it was a waste of money to spend $50/month on the service.

We encourage MailChimp users to reconsider their relationship with a service provider that would so indiscriminately de-platform projects in this way. MailChimp is free to do as they please with their platform and free to institute whatever cowardly policies they see fit, and  their customers are likewise free to walk or never to do business with them in the first place.
