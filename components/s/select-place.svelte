<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4ugrl7ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ugrl7ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:select-place" {...props}></Icon>
