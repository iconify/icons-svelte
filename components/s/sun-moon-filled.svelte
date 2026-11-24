<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rudnz8bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rudnz8bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sun-moon-filled" {...props}></Icon>
