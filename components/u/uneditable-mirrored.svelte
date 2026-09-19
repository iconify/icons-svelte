<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2u_hlbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f2u_hlbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:uneditable-mirrored" {...props}></Icon>
