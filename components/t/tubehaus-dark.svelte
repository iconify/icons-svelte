<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by3dv2b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="by3dv2b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tubehaus-dark" {...props}></Icon>
