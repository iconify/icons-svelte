<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emu812b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="emu812b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:secrover-dark" {...props}></Icon>
