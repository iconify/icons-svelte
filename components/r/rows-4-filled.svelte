<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw96_ebrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw96_ebrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rows-4-filled" {...props}></Icon>
