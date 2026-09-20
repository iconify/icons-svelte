<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1w56ebrl.css';
import '../../css/c/c0xyygbvy.css';
import '../../css/u/u1e8aucpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG591VZcVx" x1="-25.047" x2="537.047" y1="93.737" y2="418.263" gradientUnits="userSpaceOnUse"><stop offset="0" class="v1w56ebrl"/><stop offset="1" class="c0xyygbvy"/></linearGradient><path fill="url(#SVG591VZcVx)" class="u1e8aucpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:strava-dark" {...props}></Icon>
