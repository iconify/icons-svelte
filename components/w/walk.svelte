<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt10hccok.css';
import '../../css/z/z_2v24bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="yt10hccok"/><path class="z_2v24bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:walk" {...props}></Icon>
