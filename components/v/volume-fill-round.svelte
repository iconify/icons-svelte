<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri78dbu8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri78dbu8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-fill-round" {...props}></Icon>
