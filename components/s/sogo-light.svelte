<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsni9xlze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jsni9xlze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sogo-light" {...props}></Icon>
