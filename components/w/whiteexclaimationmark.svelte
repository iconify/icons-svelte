<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czs2bxbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="czs2bxbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whiteexclaimationmark" {...props}></Icon>
