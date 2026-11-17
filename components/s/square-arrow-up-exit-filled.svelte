<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgf5td-lq.css';
import '../../css/z/zgpt8x30u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgf5td-lq"/><path class="zgpt8x30u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-up-exit-filled" {...props}></Icon>
