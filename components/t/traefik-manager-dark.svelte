<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4ks7abcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4ks7abcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traefik-manager-dark" {...props}></Icon>
