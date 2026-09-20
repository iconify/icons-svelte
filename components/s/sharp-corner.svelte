<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0rm_840l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0rm_840l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sharp-corner" {...props}></Icon>
