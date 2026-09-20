<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udy4foket.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udy4foket"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sidero-omni-dark" {...props}></Icon>
