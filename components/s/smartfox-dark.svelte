<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x96h1bhdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x96h1bhdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smartfox-dark" {...props}></Icon>
