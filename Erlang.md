[1��riak_sysmon](https://github.com/basho/riak_sysmon)

��erlang:system_monitor/0,1,2�ķ�װ������ķ���ϵͳ�д��ڵ�long_gc��large_heap�������������������ʹ���еġ�refc binary���͡�OOM����

[2��recon](https://github.com/ferd/recon)

��װ��erlang:process_info/1,2���������ṩ��TOPN��feature��recon_alloc��װ�˶���������ڲ��ڴ��ʹ�����Ĳ�ѯ��
������ˣ�recon�ṩ��һ�ֽ��ƶ���Erlang����CPU���ĵķ�����Erlang tool --recon��memoryleak�ļ�顣�������ʹ���еġ�Erlang����CPU���Ķ���������refc binary���������ṩ�����ֱ��������õ����ĸо���

[3��eper/redbug](https://github.com/massemanet/eper)

�տ�ʼ�Ӵ�Erlangʱ�������ṩ��һ�ִ�����Է�������־��Ȼ�����ַ�ʽ̫�����ţ�ʹ�������ǳ��鷳��
redbug�Ƕ�Erlangϵͳ��dbgģ��ķ�װ���ṩ�˷ǳ���ȫ��Ч�Ĵ�����Է�ʽ������ȫ��������������˵��ȷʵ̫����Ҫ�ˡ�

[4��pooler/poolboy](https://github.com/seth/pooler)

github : [seth/pooler �� GitHub](https://github.com/seth/pooler)

github :[ devinus/poolboy �� GitHub](https://github.com/devinus/poolboy)

�ء�Erlang������Ч�ʵ����⣬�ǳ����������ַ�ʽ����һ���ǳأ��ڶ�����noblock call�����������޸�ĳ�����̵���Դ���á�
�������У��������ǵ�һ�ַ��������ڶ��ֺ͵����ַ���������Erlang������Ա�Դ���У�rpcģ�飬net_kernelģ�飩���������ʹ���еġ����������⡱��

[5��jiffy](https://github.com/davisp/jiffy)

github : davisp/jiffy �� GitHub
json����⣬������nif�ģ��ܹ������ܱ�֤Ч�������ҿ���֧��return_maps�Ѿ�encode force_utf8��decode ��return_maps��ֱ�ӷ���map �������ͣ��ǳ�֮���㡣����Ȼ17��mapЧ�ʲ���ô��������18�汾���˺ܴ���Ż���

[6��entop](https://github.com/mazenharake/entop)

github : mazenharake/entop �� GitHub
��û�о���Erlang�Դ���etop��Щ���ã�entop�ṩ�˷ǳ�����Ŀ����������

[7��erlang-lz4](https://github.com/szktty/erlang-lz4)

github : szktty/erlang-lz4 �� GitHub
������Erlangϵͳ����������ϵͳ���������Ķ��ǡ�С��Ϣ������㡱����֮Erlang��Ϣ������ֵ���ݵķ�ʽ�����ڴ��message����΢��һ��ѹ������ȡ��ȡ�����벻����Ч����������һ�ԣ�lz4 ���㷨����Google ֮��

[8��sync](https://github.com/rustyio/sync)

github : rustyio/sync �� GitHub
on-the-fly recompiling and reloading in Erlang. �������߹���Ч�ʣ�����Ӷ�����������compile��generate��������Ҫע����ǣ����ֻ���ڿ��������¡�
�����ȸ�����߶߶���䣺
> 1����supervisor����ɾ gen_server child �ȸ���ʧ�ܣ�Ŀǰ�޽⣬�����޸�supervisorԴ����
> 2��gen_server record ��ɾ�ֶΣ�������� ��ʹ��proplists�ֶ�ֵ�������ǡ�map�ֶ�ֵ��
> 3��gen_server init �����߼��޷��ȸ�������취����дcode_change ����
> ���ڳ�����߼����룬�ȸ�������ûʲô����

[9��erlang_term](https://github.com/okeuday/erlang_term)

github : okeuday/erlang_term �� GitHub
����һ��Term��ETS���У��ѵ���Ӧ��֪�����Term����ռ���˶����ڴ�ռ���Ҫsendһ�����message����һ�����̣�������һ���ڴ�ռ�ô�С���������������²�̫�á�erlang_term������Ϊ����С���ߡ�[Erlang ets -- something about cache continue](http://www.cnblogs.com/--00/p/erlang_ets_something_about_cache_continue.html)

[10��folsom](https://github.com/boundary/folsom)

github : boundary/folsom �� GitHub
�ṩ�˶���Metrics ģ�ͣ������Լ���Ӧ�ó�����ѡ��ͬ��ģ�;��С��ڲ���Ҫʹ��ets:update_counter/3,4������Ч�����б�֤��

[11��ej](https://github.com/seth/ej)

github : seth/ej �� GitHub
Helper module for working with Erlang terms representing JSON
���Ծ�֪����û����˼���ò������ˡ�

[12��task](https://github.com/redink-toys/task)

github : redink-toys/task �� GitHub
����������һ������˼�ĳ�������������һ����ͨ���̣���10W�������б����뽫�����֮�󣬽�1/2������1/4���б�д�뵽ETS���У�Ȼ����к����Ĳ������������������������һЩ�в�������������̾ͻᱻ��ס����ΪGC��Erlang��GC����STW�������п��ܻ�STP�������ǵ�ETS������ڲ�ͬ�Ľ���֮�乲�����ݣ��ҾͿ�������������spawnһ�����̣�����������ȥִ�й��ˡ�д�������Ȼ����������������ڽ���֮��GC�Ǻܼ򵥿��ٵġ�
task����һ��spawn��receive�ļ򵥷�װ��

[13��xref_runner](https://github.com/inaka/xref_runner)

github : inaka/xref_runner �� GitHub
[��xref��飺�ƴ�Erlang ���� -- Xref ʵ��](http://www.cnblogs.com/--00/p/code_erlang_xref.html)

[14. inaka/elvis](https://github.com/inaka/elvis)

Erlang����style��飬֧��github webhook��֧��Erlang shell�����м�顣����inaka/erlang_guidelines�ṩ�˶Գ�ѧ�ߺ��Ѻõ�style guide����һ��ʼ�������õĴ����ʽ�ô��ܴ�

[15. inaka/xref_runner](https://github.com/inaka/xref_runner)

��xref�ģ� @redink �Ѿ���������

[16. inaka/apns4erl](https://github.com/inaka/apns4erl)

�þ������iOS APNS���ͷ���

[17. inaka/shotgun](https://github.com/inaka/shotgun)

��ninenines/gun�ķ�װ��֧��SSE (Server-sent Events) handling

[18. inaka/worker_pool](https://github.com/inaka/worker_pool)

�ṩ��poolboy��������worker poolʵ�֣�֧�ֶ���worker��ת����

����whisper1, tigertext, inaka����˾����˾��Github����ӭΧ�ۣ�����inaka�������ϵ�repo��

�ٰ���һ��[Erlang Makefile](https://github.com/ninenines/erlang.mk) ����Ȼ���ں�һЩ��Ŀ�����ݶ��ҹ��ܻ������ƣ�����rebar��ȣ�erlang.mk���������˲���������ٶȡ�����Erlang.mk֮��о������ٶȿ��˼�����


˵���ӡ�
[benoitc/hackney](https://github.com/benoitc/hackney) �Ǹ��ӡ�Hackney�Ǹ��ӡ�Hackney�Ǹ��ӡ���Ȼƴmulti-part�ܺ��ã����ǽ���ֻʹ��hackney_lib���ṩ�ĺ�����װ����ʹ�ñ��http�ⷢ��Hackney pool�кܶ಻�ɸ��ֵ�δ֪���⡣
