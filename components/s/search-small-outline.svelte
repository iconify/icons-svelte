<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1oz6gbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y1oz6gbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:search-small-outline" {...props}></Icon>
