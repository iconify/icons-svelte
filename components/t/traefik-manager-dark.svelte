<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx2jtu4ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zx2jtu4ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traefik-manager-dark" {...props}></Icon>
