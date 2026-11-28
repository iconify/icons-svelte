<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz2qqub9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz2qqub9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-round-corner-solid" {...props}></Icon>
