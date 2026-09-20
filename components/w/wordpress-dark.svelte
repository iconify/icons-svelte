<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9ih55fgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9ih55fgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wordpress-dark" {...props}></Icon>
