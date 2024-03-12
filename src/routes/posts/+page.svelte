<svelte:head>
	<title>Posts</title>
	<meta name="description" content="Blog posts" />
</svelte:head>

<script>
  // export let data;
</script>

<div>
  <h1>Posts</h1>
    <div class="post">
      <a href={`/posts/post1`}>Blog Post 1</a>
      <p>Description of the post...</p>
    </div>
    <div class="post">
      <a href={`/posts/post2`}>Blog Post 2</a>
      <p>Description of the post...</p>
    </div>
  <!-- {#each data.posts as post (post.slug)}
    <h2>
        <a href={`/posts/${post.slug}`}>{post.title}</a>
    </h2>
  {/each} -->
</div>
