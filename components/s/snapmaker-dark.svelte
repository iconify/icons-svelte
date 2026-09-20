<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcm2r0bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dcm2r0bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapmaker-dark" {...props}></Icon>
