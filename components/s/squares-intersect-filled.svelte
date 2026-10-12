<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjo6adcjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjo6adcjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:squares-intersect-filled" {...props}></Icon>
