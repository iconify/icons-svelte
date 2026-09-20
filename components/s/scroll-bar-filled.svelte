<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lenrsb8cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lenrsb8cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:scroll-bar-filled" {...props}></Icon>
