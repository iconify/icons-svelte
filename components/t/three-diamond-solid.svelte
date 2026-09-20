<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzzdn-bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzzdn-bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:three-diamond-solid" {...props}></Icon>
