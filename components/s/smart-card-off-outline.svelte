<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvi_e_b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvi_e_b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smart-card-off-outline" {...props}></Icon>
