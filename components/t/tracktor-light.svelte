<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piigrn6ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="piigrn6ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tracktor-light" {...props}></Icon>
