<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d87tf4g5x.css';
import '../../css/b/btx7j3qro.css';
import '../../css/v/vpayovg2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="d87tf4g5x"/><path class="btx7j3qro"/><path class="vpayovg2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:zip" {...props}></Icon>
