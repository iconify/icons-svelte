<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxf1tkb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxf1tkb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-slice" {...props}></Icon>
