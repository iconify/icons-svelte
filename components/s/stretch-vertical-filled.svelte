<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmto18o1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmto18o1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:stretch-vertical-filled" {...props}></Icon>
