# Test-DrivenDevelopmentDemo

# To-do list Feature Specs:

## Story: Costumer requests to see their to-do list

### Narrative 

```
As a costumer
I want the app load my to-do list
So I can always see what I need to do
```

#### Scenarios (Acceptance criteria)

```
Given the costumer
 When the costumer requests to see their list
 Then the app should display their list
```

## Use Cases

### Load to-do list 

#### Inputs:
- List name

#### Primary course (happy path):
1. Exceute "Load List" command with above data.
2. System downloads data.
3. System validates downloaded data.
4. System creates list from valid data.
5. System delivers list.

#### Invalid data - error course (sad path):
1. System delivers invalid data error.
