<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucfux7brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ucfux7brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sidero-dark" {...props}></Icon>
