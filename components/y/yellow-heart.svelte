<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wak1glb2p.css';
import '../../css/f/fq4_qkb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wak1glb2p"/><path class="fq4_qkb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:yellow-heart" {...props}></Icon>
