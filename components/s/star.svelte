<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn_z0tbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn_z0tbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:star" {...props}></Icon>
