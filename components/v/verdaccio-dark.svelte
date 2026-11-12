<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi466ubef.css';
import '../../css/s/sf5m5dbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wi466ubef"/><path class="sf5m5dbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:verdaccio-dark" {...props}></Icon>
