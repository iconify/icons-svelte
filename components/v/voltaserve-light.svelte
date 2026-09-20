<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbcg6dbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbcg6dbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voltaserve-light" {...props}></Icon>
