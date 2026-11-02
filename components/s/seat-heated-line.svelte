<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3j62ibaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3j62ibaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:seat-heated-line" {...props}></Icon>
