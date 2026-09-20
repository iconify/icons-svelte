<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm5_ombgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gm5_ombgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voxmedia-coral-light" {...props}></Icon>
