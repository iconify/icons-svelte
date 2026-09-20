<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwa_69bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwa_69bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtube-shorts-light" {...props}></Icon>
