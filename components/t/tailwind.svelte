<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8_g_z5oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8_g_z5oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tailwind" {...props}></Icon>
