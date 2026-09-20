<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d00see32g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d00see32g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sound-mute-filled" {...props}></Icon>
