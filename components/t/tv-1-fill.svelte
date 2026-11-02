<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-051sx2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-051sx2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tv-1-fill" {...props}></Icon>
