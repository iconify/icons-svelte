<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipf2zhprn.css';
import '../../css/c/cvimsccvy.css';
import '../../css/i/i5lmhc31t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="ipf2zhprn"/><path class="cvimsccvy"/><path class="i5lmhc31t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:upload" {...props}></Icon>
