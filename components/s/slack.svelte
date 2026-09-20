<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk0s6nbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk0s6nbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:slack" {...props}></Icon>
