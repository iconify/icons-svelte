<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l07pnbbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l07pnbbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:speech-bubble-question" {...props}></Icon>
