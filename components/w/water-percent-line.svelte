<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br6g_vlcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br6g_vlcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:water-percent-line" {...props}></Icon>
