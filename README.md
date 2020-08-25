# proxy_parser
Парсит прокси с сайта http://free-proxy.cz/en/proxylist/country/all/https/ping/all . 

a = proxy_parser() 
a.get_poxy('https',1)
print (a.server[-1]['ip'], a.server[1]['port'] ,  a.server[1]['protocol'] , len(a.server), a.next_proxy())
