<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apgdoz4ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="apgdoz4ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:toyota-light" {...props}></Icon>
