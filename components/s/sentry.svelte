<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q26_qtrtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":227};
const content = `<path class="q26_qtrtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sentry" {...props}></Icon>
