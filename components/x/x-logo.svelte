<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm_bzwokc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jm_bzwokc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:x-logo" {...props}></Icon>
