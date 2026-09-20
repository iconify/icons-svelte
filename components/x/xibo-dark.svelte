<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf-_vsrid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uf-_vsrid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xibo-dark" {...props}></Icon>
