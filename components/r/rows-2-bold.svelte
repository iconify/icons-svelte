<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf86qebjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf86qebjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-2-bold" {...props}></Icon>
