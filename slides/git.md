## Git?!

![image git](images/git.png "Image Git")

note:
    real value is when we moved this process into git

    so our workflow is
    that screenshots of our app are taken during scenarios and committed
    then if any subsequent change causes them to differ then they will appear as a diff

    this is then included in the MR
    and then these become part of our peer review

    dis - cost associated with checking these images
    adv - spot visual issues that are not covered by existing tests
    dont make there way into production
    faster QA cycle as fewer bugs are found
    customers have more faith in product quality
    side benefit - higlights leaks if random screens are breaking when you are working on separate feature
