<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx2prybdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx2prybdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:spirals" {...props}></Icon>
