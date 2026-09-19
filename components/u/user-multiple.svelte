<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hicwgrm3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hicwgrm3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-multiple" {...props}></Icon>
