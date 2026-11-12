<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi-7frb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fi-7frb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonarr-light" {...props}></Icon>
