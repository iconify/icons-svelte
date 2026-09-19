<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbb35bbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wbb35bbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:target-two" {...props}></Icon>
