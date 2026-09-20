<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4jpk8bpd.css';
import '../../css/r/rwmxrkntq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m4jpk8bpd"/><path class="rwmxrkntq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tracearr-light" {...props}></Icon>
