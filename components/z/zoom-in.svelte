<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs6pq-bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cs6pq-bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:zoom-in" {...props}></Icon>
