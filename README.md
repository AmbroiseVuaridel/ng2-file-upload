this is an exact copy of v1.3.0 of https://www.npmjs.com/package/ng2-file-upload
the only difference is the modification for the issue
Access to XMLHttpRequest at 'http://example.com/test' from origin 'http://localhost:8100' has been blocked by CORS policy: Response to preflight request doesn't pass access control check: The value of the 'Access-Control-Allow-Origin' header in the response must not be the wildcard '*' when the request's credentials mode is 'include'. The credentials mode of requests initiated by the XMLHttpRequest is controlled by the withCredentials attribute.
I went to : ‎⁨⁨node_modules⁩/ng2-file-upload⁩/file-upload⁩ and commented : // xhr.withCredentials = item.withCredentials;
