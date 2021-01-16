# Ringba Algorithm Code Test

Please fill in the implementation of the `HighlyOptimizedThreadSafeInMemoryDuplicateCheckService` service. This service only job is to report if a id has been seen before. The service must meet the following specs.
- Service is in memory and does not persist data
- Service is thread safe
- Service is optimized for *memory*, *CPU*, and *locking*
- Service must handle large datasets
- Service can not tolerate duplicates but can tolerate false positives with an error rate equal or less than 1%



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
