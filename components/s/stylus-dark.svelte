<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqeiku3dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqeiku3dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stylus-dark" {...props}></Icon>
