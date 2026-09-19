<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qde_akxdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qde_akxdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-left-01" {...props}></Icon>
