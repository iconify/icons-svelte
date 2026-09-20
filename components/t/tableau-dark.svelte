<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1b0pbbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f1b0pbbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tableau-dark" {...props}></Icon>
