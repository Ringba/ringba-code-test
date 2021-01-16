# Ringba Algorithm Code Test

Please fill in the implementation of the `HighlyOptimizedThreadSafeInMemoryDuplicateCheckService` service. This service only job is to report if a id has been seen before. The service must meet the following specs.
- Service is in memory and does not persist data
- Service is thread safe
- Service is optimized for *memory*, *CPU*, and *locking*
- Service must handle large datasets
- Service can not tolerate duplicates but can tolerate false positives with an error rate equal or less than 1%
- Service will not utilize any third-party libraries and all code must be native .net core 5

_The code below can be changed in any way but the name of the service must remain the same._



```
namespace ringba_code_test
{

    public class HighlyOptimizedThreadSafeInMemoryDuplicateCheckService : IDuplicateCheckService
    {
       
        public bool IsThisTheFirstTimeWeHaveSeen(int id)
        {
            if (id < 0)
            {
                throw new ArgumentOutOfRangeException("id");
            }

            throw new NotImplementedException();
        }
    }

    public class HighlyOptimizedThreadSafeInMemoryDuplicateCheckServiceTest
    {
        [Fact]
        public void IsThisTheFirstTimeWeHaveSeenTest()
        {
            throw new NotImplementedException();
        }

    }
}
```
