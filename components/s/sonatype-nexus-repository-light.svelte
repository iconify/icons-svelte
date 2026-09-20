<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxfif4y9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxfif4y9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonatype-nexus-repository-light" {...props}></Icon>
