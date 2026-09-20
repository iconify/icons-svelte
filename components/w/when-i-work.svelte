<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei6p8430q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei6p8430q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:when-i-work" {...props}></Icon>
