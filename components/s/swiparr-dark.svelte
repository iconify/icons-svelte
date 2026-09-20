<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5r16bcmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5r16bcmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swiparr-dark" {...props}></Icon>
