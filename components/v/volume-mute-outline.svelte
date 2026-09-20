<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krrro6b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="krrro6b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:volume-mute-outline" {...props}></Icon>
