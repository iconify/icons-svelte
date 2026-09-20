<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g46yy7bor.css';
import '../../css/w/wdnbtobig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="g46yy7bor"/><path class="wdnbtobig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:strava-statistics" {...props}></Icon>
