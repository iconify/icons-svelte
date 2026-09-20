<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyv0nyqej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyv0nyqej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:za-sort-ascending-letters-line" {...props}></Icon>
