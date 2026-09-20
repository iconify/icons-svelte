<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c24on08cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c24on08cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:travstats-light" {...props}></Icon>
