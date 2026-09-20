<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6riaebrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6riaebrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-polygon-variant" {...props}></Icon>
