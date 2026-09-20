<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvs72d4fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvs72d4fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:viaplay-light" {...props}></Icon>
