# hussain
import PullToRefresh from 'react-simple-pull-to-refresh';


// ...

return (
  <PullToRefresh onRefresh={handleRefresh}>
    <ul>
      {list.map((item, index) => (
        <li key={index}>{item}</li>
      ))}
    </ul>
  </PullToRefresh>
);

// ...


// ...

return (
  <PullToRefresh onRefresh={handleRefresh} canFetchMore={true} onFetchMore={handleFetchMore}>
    <ul>
      {list.map((item, index) => (
        <li key={index}>{item}</li>
      ))}
    </ul>
  </PullToRefresh>
);

// ...
