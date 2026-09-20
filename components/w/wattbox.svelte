<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfc-29bll.css';
import '../../css/x/x_p186bjn.css';
import '../../css/a/a0c8erb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfc-29bll"/><path class="x_p186bjn"/><path class="a0c8erb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wattbox" {...props}></Icon>
