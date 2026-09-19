<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re2q06o0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re2q06o0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonoff-0p1" {...props}></Icon>
