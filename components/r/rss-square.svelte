<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqvveuaft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qqvveuaft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:rss-square" {...props}></Icon>
