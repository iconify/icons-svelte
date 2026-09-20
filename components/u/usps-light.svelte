<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u90aztbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u90aztbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:usps-light" {...props}></Icon>
