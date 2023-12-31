# FrozenSet

Good for API response, new in .NET 8.
<img width="801" alt="image" src="https://github.com/jctechhub/fork-AsyncAwaitBestPractices/assets/24492674/32a6c314-8456-45db-9b96-78a5c99556c8">


# Pattern: Multiple async calls

use of the following keywords: 
- await foreach
- IAsyncEnumerable<StoryModel>
- Task.WhenAny

Note: the use of '.ConfigureAwait(false);', is to make sure that the background thread doesn't lock up main thread.     

<img width="1045" alt="image" src="https://github.com/jctechhub/fork-AsyncAwaitBestPractices/assets/24492674/2f3044a9-1ee4-4e61-95ca-c3608285421f">

# IAsyncDisposable
<img width="982" alt="image" src="https://github.com/jctechhub/fork-AsyncAwaitBestPractices/assets/24492674/3eb0c30b-4803-49ba-8a98-2bfcae1e78d5">


# ValueTask

Use it when 9/10 calls are just returning results without call await function. 

<img width="865" alt="image" src="https://github.com/jctechhub/fork-AsyncAwaitBestPractices/assets/24492674/32f81b99-d4ef-4bec-aba1-f4ece4adbf20">
