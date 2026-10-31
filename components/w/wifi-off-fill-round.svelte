<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwo1k3bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwo1k3bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wifi-off-fill-round" {...props}></Icon>
