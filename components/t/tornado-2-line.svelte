<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4t75tbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4t75tbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tornado-2-line" {...props}></Icon>
