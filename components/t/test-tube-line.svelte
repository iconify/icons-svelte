<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unqyvfb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unqyvfb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:test-tube-line" {...props}></Icon>
