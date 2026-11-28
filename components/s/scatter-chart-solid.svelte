<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjrbj5liv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjrbj5liv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scatter-chart-solid" {...props}></Icon>
