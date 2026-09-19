<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs23i3x1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gs23i3x1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:thumbs-up" {...props}></Icon>
