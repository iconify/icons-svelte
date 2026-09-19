<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9bm09bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u9bm09bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:the-movie-database" {...props}></Icon>
