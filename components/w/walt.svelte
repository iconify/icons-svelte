<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa-a72udx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wa-a72udx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:walt" {...props}></Icon>
