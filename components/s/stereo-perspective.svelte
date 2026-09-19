<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuzjs9mod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cuzjs9mod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:stereo-perspective" {...props}></Icon>
