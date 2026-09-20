<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5sc99b2m.css';
import '../../css/m/m3i3t-iqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5sc99b2m"/><path class="m3i3t-iqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spooty-dark" {...props}></Icon>
