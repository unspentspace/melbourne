# Customers
customer = anyone who pays for a membership or event/workshop at unspent.space
member = a paying member who generally uses the space during the day.

List of customer types with anticipated percentage of membership base.
1. Digital Nomad (5%)
2. Professional Contractor Interested in Bitcoin (45%)
3. Maxi Poor Stacker (5%)
4. Open Source Bitcoin Contributor (5%)
5. Work from home employee passionate about bitcoin (30%)
6. Employee from a bitcoin or bitcoin-friendly company e.g. CashApp (10%)


## 1. Digital Nomad

```
{
  type: 'digitalNomad',
  professions: [
    'software developer',
    'designer',
    'gap year'
    'early retired'
  ],
  bitcoinKnowledge: [
    'medium'
  ],
  longtermCustomer: false,
  comfortRequired: 'low'
  activities: [
    'coworking',
    'workshop',
    'library',
    'privateMeeting',
    'events'
  ]
}
```

## 2. Professional Contractor Interested in Bitcoin

```
{
  type: 'contractor',
  professions: [
    'itConsultant',
    'designer',
    
  ],
  bitcoinKnowledge: [
    'medium'
  ],
  longtermCustomer: true,
  comfortRequired: 'high'
  activities: [
    'coworking',
    'workshop',
    'library',
    'privateMeeting'
  ]
}
```

## 3. Maxi Poor Stacker
```
{
  type: 'maxiPoorStacker',
  description: 'Hardcore bitcoiner who values stacking above all else.'
  professions: [
    'constructionWorker',
    'student',
    'banker'
  ],
  bitcoinKnowledge: [
    'high'
  ],
  longtermCustomer: true,
  comfortRequired: 'low'
  activities: [
    'events',
    'workshop',
    'library',
    'podcasting'
  ],
  spareMoney: 'low'
}
```

## 4. Open Source Bitcoin Contributor
```
{
  type: 'openSourceBitcoinContributor',
  description: 'An open source bitcoin contributor, either part or full time, generally without a salary from an employer.'
  professions: [
    'programmer',
    'cryptographer',
    'banker'
  ],
  bitcoinKnowledge: [
    'high'
  ],
  longtermCustomer: true,
  comfortRequired: 'low'
  activities: [
    'coworking',
    'events',
    'workshop',
    'library',
    'podcasting',
    'privateMeeting'
  ],
  spareMoney: 'low'
}
```

## 5. Work from home professional passionate about bitcoin
```
{
  type: 'workFromHomeProfessionalBitcoiner',
  description: 'A professional, usually an employee, who mainly works from home, sometimes at the company office. They are quite passionate and interested in Bitcoin, and have a decent amount of spare cash.'
  professions: [
    'finance',
    'law',
    'construction',
    'engineering',
    'information technology'
  ],
  bitcoinKnowledge: [
    'medium'
  ],
  longtermCustomer: true,
  comfortRequired: 'medium'
  activities: [
    'coworking',
    'events',
    'library',
    'privateMeeting'
  ],
  spareMoney: 'high'
}
```


