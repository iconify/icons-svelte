<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg4d2loez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg4d2loez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:swimming-line" {...props}></Icon>
