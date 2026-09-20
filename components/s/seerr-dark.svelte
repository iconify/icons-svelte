<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_mg58bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_mg58bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seerr-dark" {...props}></Icon>
