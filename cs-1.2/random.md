# Random

* random.random -&gt; float in range \[0, 1\) can be 0 but never 1
* random.uniform -&gt; float in range\[a,b\] includes both endpoints
* random.int -&gt; int in range \[a, b\] includes both endpoints
* random.randrange -&gt; int in range \[a, b\) excludes b \(b-1\)
* random.choice\(items\) -&gt; item from list \(uses randrange\) with uniform probability
* random.choices\(items, n\) -&gt; list of num items
* random.choices\(items, weights\)-&gt; list of items weighted probability

