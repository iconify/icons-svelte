<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr4-vob_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr4-vob_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-clear-formatting" {...props}></Icon>
