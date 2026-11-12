<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i86vmwb3r.css';
import '../../css/c/cogmg3blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i86vmwb3r"/><path class="cogmg3blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamystats-light" {...props}></Icon>
