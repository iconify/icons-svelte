<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feogx6j2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="feogx6j2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:torsher-dark" {...props}></Icon>
