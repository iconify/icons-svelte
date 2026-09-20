<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hux5aggyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hux5aggyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-align-justify-box" {...props}></Icon>
