<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z477j3bdr.css';
import '../../css/g/gno1t7swb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="z477j3bdr"/><path class="gno1t7swb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:trash-bin" {...props}></Icon>
