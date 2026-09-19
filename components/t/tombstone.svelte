<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv1r_vbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xv1r_vbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tombstone" {...props}></Icon>
