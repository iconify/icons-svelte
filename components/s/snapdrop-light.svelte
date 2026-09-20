<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw4zcdvad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rw4zcdvad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapdrop-light" {...props}></Icon>
