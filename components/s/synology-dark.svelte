<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbnd3dbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lbnd3dbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synology-dark" {...props}></Icon>
