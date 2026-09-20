<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tux5omtmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tux5omtmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-star" {...props}></Icon>
