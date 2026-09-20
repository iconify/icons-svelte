<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/u/u1e8aucpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGArkTYdlF" x1="-25.047" x2="537.047" y1="93.737" y2="418.263" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGArkTYdlF)" class="u1e8aucpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:strava-light" {...props}></Icon>
