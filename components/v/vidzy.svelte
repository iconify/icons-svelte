<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hopwrdk5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hopwrdk5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vidzy" {...props}></Icon>
