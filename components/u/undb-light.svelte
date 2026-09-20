<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icx04h3_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="icx04h3_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:undb-light" {...props}></Icon>
