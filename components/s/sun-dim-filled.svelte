<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyc18ebrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyc18ebrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sun-dim-filled" {...props}></Icon>
