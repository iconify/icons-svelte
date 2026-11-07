<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm6jvmbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pm6jvmbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traceway" {...props}></Icon>
