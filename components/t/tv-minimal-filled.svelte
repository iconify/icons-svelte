<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu531kbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu531kbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tv-minimal-filled" {...props}></Icon>
