<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6la11b1v.css';
import '../../css/o/okcf14hbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6la11b1v"/><path class="okcf14hbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:search-magnifier" {...props}></Icon>
