<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq5q6vrgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vq5q6vrgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:turnkey-linux-light" {...props}></Icon>
