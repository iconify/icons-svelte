<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5_uzpblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5_uzpblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scale-filled" {...props}></Icon>
