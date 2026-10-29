<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axaf_tbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axaf_tbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-low-solid" {...props}></Icon>
