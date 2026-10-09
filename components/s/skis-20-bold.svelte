<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le1xlvbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="le1xlvbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skis-20-bold" {...props}></Icon>
