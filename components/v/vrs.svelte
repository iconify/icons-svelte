<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7wkc6bmm.css';
import '../../css/u/u0c79lbga.css';
import '../../css/j/jvytkl3_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":121,"height":121};
const content = `<circle class="w7wkc6bmm"/><path class="u0c79lbga"/><path class="jvytkl3_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vrs" {...props}></Icon>
