<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_wt-ubrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i_wt-ubrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:swimming" {...props}></Icon>
