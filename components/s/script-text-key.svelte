<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_v3vdbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_v3vdbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:script-text-key" {...props}></Icon>
