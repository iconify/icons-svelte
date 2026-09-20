<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzxr2obon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzxr2obon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sound-off" {...props}></Icon>
