<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjj7fxdmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wjj7fxdmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:weam-dark" {...props}></Icon>
