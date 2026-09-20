<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otuf-7iix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="otuf-7iix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xplicittrust-dark" {...props}></Icon>
