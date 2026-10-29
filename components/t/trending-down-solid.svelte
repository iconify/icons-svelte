<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj-s7ache.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj-s7ache"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trending-down-solid" {...props}></Icon>
