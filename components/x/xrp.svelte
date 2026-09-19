<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk9xfo3pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pk9xfo3pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:xrp" {...props}></Icon>
