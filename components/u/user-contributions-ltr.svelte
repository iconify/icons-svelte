<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlr1o39qv.css';
import '../../css/c/cg7d2pfom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jlr1o39qv"/><circle class="cg7d2pfom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-contributions-ltr" {...props}></Icon>
