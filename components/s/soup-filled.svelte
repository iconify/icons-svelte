<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwosufbcj.css';
import '../../css/r/re3b6ubpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwosufbcj"/><path class="re3b6ubpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:soup-filled" {...props}></Icon>
