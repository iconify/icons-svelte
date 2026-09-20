<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7gd6cbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z7gd6cbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vertiv-light" {...props}></Icon>
