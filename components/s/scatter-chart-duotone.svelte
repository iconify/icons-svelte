<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo0tzaczo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo0tzaczo primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scatter-chart-duotone" {...props}></Icon>
