<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo-l4qbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mo-l4qbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:rss" {...props}></Icon>
