<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twipirh2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="twipirh2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vimeo-light" {...props}></Icon>
