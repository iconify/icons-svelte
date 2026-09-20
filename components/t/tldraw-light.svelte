<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o80rageed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o80rageed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tldraw-light" {...props}></Icon>
