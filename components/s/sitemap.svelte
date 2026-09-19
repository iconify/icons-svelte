<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g82h75bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="g82h75bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sitemap" {...props}></Icon>
