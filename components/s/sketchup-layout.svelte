<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htglb-b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="htglb-b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sketchup-layout" {...props}></Icon>
