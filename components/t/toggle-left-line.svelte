<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lek2xnz1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lek2xnz1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-left-line" {...props}></Icon>
