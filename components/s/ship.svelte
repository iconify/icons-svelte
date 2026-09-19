<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0q4tlbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1792};
const content = `<path class="t0q4tlbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:ship" {...props}></Icon>
