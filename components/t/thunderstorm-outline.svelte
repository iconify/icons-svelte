<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw_3i8bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vw_3i8bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:thunderstorm-outline" {...props}></Icon>
