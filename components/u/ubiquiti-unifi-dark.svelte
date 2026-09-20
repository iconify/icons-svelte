<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_9orj6ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u_9orj6ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ubiquiti-unifi-dark" {...props}></Icon>
