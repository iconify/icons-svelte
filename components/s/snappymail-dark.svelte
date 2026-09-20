<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqx2n2bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fqx2n2bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snappymail-dark" {...props}></Icon>
