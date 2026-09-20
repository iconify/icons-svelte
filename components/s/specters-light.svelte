<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv6lnpbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sv6lnpbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:specters-light" {...props}></Icon>
