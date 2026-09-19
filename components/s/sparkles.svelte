<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk0wdd05p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nk0wdd05p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:sparkles" {...props}></Icon>
