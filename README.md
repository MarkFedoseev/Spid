# Spid
<p align="center">
  <img src="https://user-images.githubusercontent.com/87077242/194978973-19e30ad5-97ee-4688-be7f-652a229a6f26.jpg" width="300">
</p>

An emplementation of popular bot called spider or web crawler. Name "spid" refers to original name but was shortened due small functionality (just for now :)) and an internet meme

# How to use

This bot is pretty simple to use:
```
python spid.py [-h] [--deep DEEPNESS] [--link] [--script] [--img] domain
```
where:

```domain``` is domain to start the search with

```DEEPNESS``` sets the deepness of search (spid will stop search in branch when its length become more then DEEPNESS value)

```--link``` with this argument spid will explore URLs in ```<link>``` tag

```--script``` with this argument spid will explore URLs in ```<script>``` tag

```--img``` with this argument spid will explore URLs in ```<img>``` tag

# Output

Bot outputs summary with:

- Number of analysed URLs
- External URLs found (URLs on websites with different domain)
- Invalid URLs found (URLs that bot couldn't parse)

Also, error log provided
