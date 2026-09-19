<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr_xxwbkp.css';
import '../../css/j/jyvikwbnh.css';
import '../../css/w/w3xf5cbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lr_xxwbkp"/><path class="jyvikwbnh"/><path class="w3xf5cbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:search-circle-outline" {...props}></Icon>
