<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obv4mibzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obv4mibzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scratch-map" {...props}></Icon>
