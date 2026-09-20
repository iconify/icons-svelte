<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di4g56bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di4g56bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ruler-off" {...props}></Icon>
