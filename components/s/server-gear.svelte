<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmwb7_bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmwb7_bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:server-gear" {...props}></Icon>
