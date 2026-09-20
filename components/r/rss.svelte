<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj1vbobrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="uj1vbobrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:rss" {...props}></Icon>
