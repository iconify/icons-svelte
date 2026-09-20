<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udzoj_brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udzoj_brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train-car-flatbed" {...props}></Icon>
