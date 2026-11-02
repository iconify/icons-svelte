<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5xkztbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5xkztbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wheel-line" {...props}></Icon>
