<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxf_ij_3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxf_ij_3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:suspicious" {...props}></Icon>
