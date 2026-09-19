<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hspnghblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hspnghblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitemediumsquare" {...props}></Icon>
