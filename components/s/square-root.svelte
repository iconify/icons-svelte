<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2a2-kvtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2a2-kvtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-root" {...props}></Icon>
