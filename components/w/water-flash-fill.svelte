<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcc_rg86w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcc_rg86w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:water-flash-fill" {...props}></Icon>
