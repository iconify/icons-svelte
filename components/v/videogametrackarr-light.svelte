<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw94zvfeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cw94zvfeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:videogametrackarr-light" {...props}></Icon>
