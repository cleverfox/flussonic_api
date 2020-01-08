# Flussonic internal API digging

Unfortunately I still found no way for compiling module compatible with flussonic's BEAM.

### DVR

lock record dvr:lock(<<"nvt.hi3518e_50h10l_s39-65d6319f2f">>,1578008940,5).

View DVR status dvr:status(<<"nvt.hi3518e_50h10l_s39-65d6319f2f">>).
```
#{bytes => 2727532860,
  locks =>
      [#{duration => 5,from => 1578008940},
       ...
       #{duration => 15,from => 1578471305}],
  ranges =>
      [#{duration => 16,from => 1578008891},
      ...
      #{duration => 661,from => 1578470772}]}
```

