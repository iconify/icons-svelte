<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce_sn057m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce_sn057m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:uac-network" {...props}></Icon>
