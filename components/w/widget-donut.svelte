<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztd7czx4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztd7czx4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:widget-donut" {...props}></Icon>
