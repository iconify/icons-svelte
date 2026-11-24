<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgf5td-lq.css';
import '../../css/m/mpdgb_2fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgf5td-lq"/><path class="mpdgb_2fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-up-exit-filled" {...props}></Icon>
