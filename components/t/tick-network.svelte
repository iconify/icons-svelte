<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af9r2o3oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af9r2o3oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tick-network" {...props}></Icon>
