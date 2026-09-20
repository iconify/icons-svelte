<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv_2wekjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bv_2wekjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sportarr-light" {...props}></Icon>
