<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-nxd9b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-nxd9b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:shield" {...props}></Icon>
