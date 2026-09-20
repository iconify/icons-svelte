<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1tcplwkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1tcplwkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sentry" {...props}></Icon>
