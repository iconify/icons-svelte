<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbw-5nbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vbw-5nbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:strava-statistics-light" {...props}></Icon>
