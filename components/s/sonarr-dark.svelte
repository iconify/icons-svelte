<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk7q64b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sk7q64b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonarr-dark" {...props}></Icon>
