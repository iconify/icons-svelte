<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_po1hivt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_po1hivt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trek-dark" {...props}></Icon>
