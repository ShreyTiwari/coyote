# ControlledSemaphoreSlim.Wait method (1 of 6)

Blocks the current task until it can enter the semaphore.

```csharp
public virtual void Wait()
```

## See Also

* class [ControlledSemaphoreSlim](../ControlledSemaphoreSlim.md)
* namespace [Microsoft.Coyote.Interception](../ControlledSemaphoreSlim.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

---

# ControlledSemaphoreSlim.Wait method (2 of 6)

Blocks the current task until it can enter the semaphore, while observing a CancellationToken.

```csharp
public virtual void Wait(CancellationToken cancellationToken)
```

| parameter | description |
| --- | --- |
| cancellationToken | The CancellationToken to observe. |

## See Also

* class [ControlledSemaphoreSlim](../ControlledSemaphoreSlim.md)
* namespace [Microsoft.Coyote.Interception](../ControlledSemaphoreSlim.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

---

# ControlledSemaphoreSlim.Wait method (3 of 6)

Blocks the current task until it can enter the semaphore, using a 32-bit signed integer that specifies the timeout.

```csharp
public virtual bool Wait(int millisecondsTimeout)
```

| parameter | description |
| --- | --- |
| millisecondsTimeout | The number of milliseconds to wait, Infinite (-1) to wait indefinitely, or zero to test the state of the wait handle and return immediately. |

## Return Value

True if the current task successfully entered the semaphore, else false.

## See Also

* class [ControlledSemaphoreSlim](../ControlledSemaphoreSlim.md)
* namespace [Microsoft.Coyote.Interception](../ControlledSemaphoreSlim.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

---

# ControlledSemaphoreSlim.Wait method (4 of 6)

Blocks the current task until it can enter the semaphore, using a TimeSpan that specifies the timeout.

```csharp
public virtual bool Wait(TimeSpan timeout)
```

| parameter | description |
| --- | --- |
| timeout | A TimeSpan that represents the number of milliseconds to wait, a TimeSpan that represents -1 milliseconds to wait indefinitely, or a TimeSpan that represents 0 milliseconds to test the wait handle and return immediately. |

## Return Value

True if the current task successfully entered the semaphore, else false.

## See Also

* class [ControlledSemaphoreSlim](../ControlledSemaphoreSlim.md)
* namespace [Microsoft.Coyote.Interception](../ControlledSemaphoreSlim.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

---

# ControlledSemaphoreSlim.Wait method (5 of 6)

Blocks the current task until it can enter the semaphore, using a 32-bit signed integer that specifies the timeout, while observing a CancellationToken.

```csharp
public virtual bool Wait(int millisecondsTimeout, CancellationToken cancellationToken)
```

| parameter | description |
| --- | --- |
| millisecondsTimeout | The number of milliseconds to wait, Infinite (-1) to wait indefinitely, or zero to test the state of the wait handle and return immediately. |
| cancellationToken | The CancellationToken to observe. |

## Return Value

True if the current task successfully entered the semaphore, else false.

## See Also

* class [ControlledSemaphoreSlim](../ControlledSemaphoreSlim.md)
* namespace [Microsoft.Coyote.Interception](../ControlledSemaphoreSlim.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

---

# ControlledSemaphoreSlim.Wait method (6 of 6)

Blocks the current task until it can enter the semaphore, using a TimeSpan that specifies the timeout, while observing a CancellationToken.

```csharp
public virtual bool Wait(TimeSpan timeout, CancellationToken cancellationToken)
```

| parameter | description |
| --- | --- |
| timeout | A TimeSpan that represents the number of milliseconds to wait, a TimeSpan that represents -1 milliseconds to wait indefinitely, or a TimeSpan that represents 0 milliseconds to test the wait handle and return immediately. |
| cancellationToken | The CancellationToken to observe. |

## Return Value

True if the current task successfully entered the semaphore, else false.

## See Also

* class [ControlledSemaphoreSlim](../ControlledSemaphoreSlim.md)
* namespace [Microsoft.Coyote.Interception](../ControlledSemaphoreSlim.md)
* assembly [Microsoft.Coyote](../../Microsoft.Coyote.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
