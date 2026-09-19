<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv57xhd9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv57xhd9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-exclude-filled" {...props}></Icon>
