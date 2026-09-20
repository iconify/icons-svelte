<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhdlf2bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lhdlf2bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windows-retro-light" {...props}></Icon>
