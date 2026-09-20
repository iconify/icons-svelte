<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvqxsz1-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rvqxsz1-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-11" {...props}></Icon>
