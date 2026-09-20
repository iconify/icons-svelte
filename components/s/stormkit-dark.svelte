<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyn4elw9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iyn4elw9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stormkit-dark" {...props}></Icon>
